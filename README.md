# pycalculator

This calculator will be updated from my main application as any bugs are discovered. <br><br>
Note: current working on output formatting for precision < 55 for linux currently testing <br><br>

- Added support for 150 decimal precision. 180 working precision.
- Added saved history
- Finished debug mode
- Added helper functions for changing theme, decimal precision and getting current history

07/08/2026

- added on right click rnd rndint and rndg for gaussian. these are alt functions like probability ect to keeps the ui cleaner <br><br>

07/04/2026 <br>
- added paste input and window popup on invalid number

scientific calculator <br>

two modes regular and scientific <br>
alternative block theme <br>
uses mpmath for arbitrary precision if installed which can also use gmpy2 package. to work at 70 decimal precision or above<br>
has exponent threshold <br>
expression history view and logging <br><br>

```python
if self.calculator is None:
  self.calculator = SCalculator(parent=None, mode="scientific", sci_threshold=6, decimals=51, theme="block", history_view=False,
                                saved_history="", rand_max=1000000, rand_min=0, logger=print, log_level="ERROR")
```
![Alt text](https://i.imgur.com/UG6QUqK.png)  ![Alt text](https://i.imgur.com/aTVRWqo.png) <br><br>

sourced from CodeQuestions <br>
https://github.com/CodeQuestions/PyQt5-Video-Book <br>
https://forum.porteus.org/go.php?https://www.youtube.com/watch?v=2XdhmcyAnH0&t=65s <br><br>
see also my pyside [alarm clock](https://github.com/dreadwrr/pyqtalarm)
