# Bundle Size Test UI Lib

This is to test how bundle size will effect when using UI libraries.

For the test, I used one component which is button from different lib and below is the bundle size table, for more info checkout the detail below.

| Library | Chunk CSS | Chunk JS | | Main CSS | Main JS | Run Time JS |
|---|---|---|---|---|---|---|
| No Lib | | 39.39 Kb | | 215 B | 489 B | 776 B |
| Ant Design | 61.62 KB | 58.75 Kb | | 149 B | 501 B | 778 B |
| Ant Design Modular | 8.83 KB | 58.63 Kb | | 149 B | 528 B | 779 B |
| Material UI | | 62.27 Kb | | 149 B | 501 B | 776 B |
| Bootstrap Styled | | 152.41 Kb | | 149 B | 505 B | 783 B |


## 01-No-Lib

In this example I have not using any library, just added simple style to button and here is the bundle size.

![No Lib Bundle Size](img/01-no-lib.png)

## 02-AntD

In this example I am using Ant Design, imported button & style and here is the bundle size.

![Ant Design Bundle Size](img/02-antd.png)

## 03-AntD-Modular

In this example I am using Ant Design, imported only button & it's style and here is the bundle size.

![Ant Design Modular Bundle Size](img/03-antd-modular.png)

I also tried to import button in two different component and check how it handle duplicate imports, here is the bundle size.

![Ant Design Modular Bundle Size](img/03-antd-modular-2.png)

## 04-Material UI

In this example I am using Material UI, imported button & linked roboto font in index.html and here is the bundle size.

![Material UI Bundle Size](img/04-material-ui.png)

## 05-Bootstrap Styled

In this example I am using Bootstrap with Styled Component, imported button and here is the bundle size.

![Bootstrap Styled Bundle Size](img/05-bootstrap-styled.png)