# mpy-a9g-ssd1306
Driver for SSD1306-driven OLEDs on A9G micropython port

Usage example:
```
from ssd1306 import SSD1306
display = SSD1306()
display.text("Get over here",0,0)
display.show()
```