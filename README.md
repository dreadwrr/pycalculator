# pycalculator
07/04/2026 <br>

- added paste input and window popup on invalid number

scientific calculator <br>
testing on going but made public as a place to store source <br><br>

two modes regular and scientific <br>
alternative block theme <br>
uses mpmath for arbitrary precision if installed which can also use gmpy2 package<br>
has exponent threshold <br>
expression history view and logging <br><br>

```python
if self.calculator is None:
  self.calculator = SCalculator(parent=None, mode="regular", sci_threshold=6, decimals=50, theme="block", history_view=False,
                                rand_max=1000000, rand_min=0, logger=print, log_level="ERROR")
```
![Alt text](https://i.imgur.com/UG6QUqK.png)  ![Alt text](https://i.imgur.com/aTVRWqo.png) <br><br>

sourced from CodeQuestions <br>
https://github.com/CodeQuestions/PyQt5-Video-Book <br>
https://forum.porteus.org/go.php?https://www.youtube.com/watch?v=2XdhmcyAnH0&t=65s <br><br>
see also my pyside ![alarm clock](https://github.com/dreadwrr/pyqtalarm)
