# Designkit Pills Tree

## Install

```bash
npm i designkit-pills-tree
```

## Usage

```html

<div class="simple_pill">
  <i></i>simple pill
</div>
<div class="sub_link">
  <ul>
    <li class="simple_pill">
      <i></i>simple pill
    </li>
    <li class="simple_pill">
      <i></i>simple pill
    </li>
    <li class="simple_pill">
      <i></i>simple pill
    </li>
  </ul>
</div>

```

## The CSS

```css
/*
//
// designkit-pills-tree
// --------------------------------------------------
*/
.sub_link {
  margin-left: 22px;
  position: relative;
}

.sub_link:before, .sub_link:after {
  background: #80C11A;
  content: "";
  height: 21px;
  left: 0;
  position: absolute;
  top: 0;
  width: 1px;
}

.sub_link:after {
  top: 6px;
  height: calc(100% - 15px);
}

.sub_link.w_checkbox:after {
  height: calc(100% - 20px);
}

.sub_link ul {
  margin: 0px 0 0 6px;
  padding: 10px 0 0 0;
}

.sub_link li {
  display: inline-table;
  margin-left: 15px;
  margin-right: 0;
  position: relative;
}

.sub_link li:before {
  background: #80C11A;
  content: "";
  height: 1px;
  left: -21px;
  position: absolute;
  top: 50%;
  width: 20px;
}

```

## Author

Artur Janas

## License

The MIT License (MIT)

Copyright (c) 2016 RightScale

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
