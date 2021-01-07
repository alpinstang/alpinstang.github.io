---
title: Thrust Game
date: "2020-12-19T22:12:03.284Z"
description: "Thrust Game"
---

I have been brushing up on Unity and C#, and made a simple 3D game. The player
has to get from a launch pad to a landing pad across an obstacle course.
Here is the ropository: 
[Thrust Repo](https://github.com/alpinstang/Thrust).

![Thrust Screenshot](./thrust-1.PNG)

Some code was written to get the oscillation on the obstacles that has some simple math.

```csharp
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

[DisallowMultipleComponent]
public class Oscillator : MonoBehaviour
{
    [SerializeField] Vector3 movementVector = new Vector3(10f, 10f, 10f);
    [SerializeField] float period = 2f; // 2 second rotation time

    Vector3 startingPos;

    // Start is called before the first frame update
    void Start()
    {
        startingPos = transform.position;
    }

    // Update is called once per frame
    void Update()
    {
        if (period <= Mathf.Epsilon) { return; };
        float cycles = Time.time / period; // grows continually from 0
        const float tau = Mathf.PI * 2; // about 6.28
        float rawSinWave = Mathf.Sin(cycles * tau); // -1 to +1

        float movementFactor = rawSinWave / 2f + 0.5f;
        Vector3 offset = movementFactor * movementVector;
        transform.position = startingPos + offset;
        
    }
}
```

Thanks for checking out the project! I will probably iterate on it in the future.