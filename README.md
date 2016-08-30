# Utilities
Common Tools to set up Python Dev Environment

#### Python 2.7
https://www.python.org/downloads/

#### Eclipse for Python
https://eclipse.org/downloads/

#### PyDev
Go to the update manager (Help > Install New Software) and add: 
http://pydev.org/updates   (for latest version)   or 
http://pydev.org/nightly   (for nightly build)  


#### 3rd Party Libraries
http://www.lfd.uci.edu/~gohlke/pythonlibs/

#### Unit Tests APIs
**Example**

```python

import unittest

class WidgetTestCase(unittest.TestCase):
    def setUp(self):
        self.widget = Widget("The widget")

    def tearDown(self):
        self.widget.dispose()
        self.widget = None

    def testDefaultSize(self):
        assert self.widget.size() == (50,50), 'incorrect default size'
        

if __name__ == '__main__':
    unittest.main()
```  
