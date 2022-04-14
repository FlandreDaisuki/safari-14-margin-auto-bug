# Safari 14 margin auto bug

![iOS-safari-14](iOS-safari-14.jpg)

![MacOS-safari-14](MacOS-safari-14.jpg)

## Solution

```diff
    main {
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
+
+     height: 100%;

      display: grid;
      grid-template-rows: auto auto 1fr;
    }
```
