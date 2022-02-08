# ME 405 Lab 3

Spinning two motors at once with the magic of scheduling

## Somebody come Git her

This lab required us to tune the period of our motor. We tested values manually.
The Kp is 50 as determinted to be most efficient by lab2. Is used for our motors while determining the motor period.
We tried 70 as our period but it produced a noticable amount of overshoot. Then we tried 10 and there was no overshoot
but we want to find the slowest period that produces no overshoot. 40 was a good period with no overshoot so we decided to stick with it. See images below.


![Kpof10](Mp70.png)

__Figure 1:__ Motor Responce, Mp = 70.


![Kpof20](Mp10.png)

__Figure 2:__ Motor Responce, Mp = 10.


![Kpof50](Mp40.png)

__Figure 3:__ Motor Responce, Mp = 40.



### Classes

* [Encoder.py](https://github.com/danrmunic/405Labs/blob/main/Lab1/src/Encoder.py)
* [motor_driver.py](https://github.com/danrmunic/405Labs/blob/main/Lab1/src/motor_driver.py)
* [main.py](https://github.com/danrmunic/405Labs/blob/main/Lab1/src/main.py)

## Documentation

* [Lab03 Documentation](https://github.com/danrmunic/405Lab3/tree)

## Website Link

* [Lab03 Website](https://danrmunic.github.io/405Labs/Lab3/docs/index.html)
