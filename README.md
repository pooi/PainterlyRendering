<h1 align=center>Painterly Rendering</h1>
<p align=center>NYU 논문을 기본으로한 이미지에 페인팅 효과를 주는 프로그램입니다.</p>
<br>

## Introduce
>참고 1 : <a href=“https://mrl.nyu.edu/projects/npr/painterly/“>https://mrl.nyu.edu/projects/npr/painterly/</a><br>
>참고 2 : <a href=“https://mrl.nyu.edu/publications/painterly98/hertzmann-siggraph98.pdf”>https://mrl.nyu.edu/publications/painterly98/hertzmann-siggraph98.pdf</a>

This program is based on the NYU paper and it is the result of the school assignment.<br>
이 프로그램은 NYU 논문을 기초로 하여 작성된 프로그램이며 학교 수업시간에 제출한 과제 결과물입니다.

<br>

## Usage
> You need opencv to use this program.<br>
> 이 프로그램을 사용하기 위해서는 opencv가 필요합니다.<br>
> <a href="http://www.opencv.org/releases.html">http://www.opencv.org/releases.html</a><br>
> 참고 : <a href="http://webnautes.tistory.com/716">http://webnautes.tistory.com/716</a>
```C
#include<opencv2/core/core.hpp>
#include<opencv2/imgproc/imgproc.hpp>
#include<opencv2/highgui/highgui.hpp>

int main(){
  ...
  IplImage * src = cvLoadImage(fileName);
  ...
}
```

<br>

## Process
This program takes 5 steps.<br>
이 프로그램은 5 스탭으로 진행됩니다.<br>
<img src="https://github.com/pooi/PainterlyRendering/blob/master/image/001.jpg">
<img src="https://github.com/pooi/PainterlyRendering/blob/master/image/002.jpg">
<br>

## Results
>Circle Effect
<img src="https://github.com/pooi/PainterlyRendering/blob/master/PainterlyRendering/PainterlyRendering/source2.jpg">
<img src="https://github.com/pooi/PainterlyRendering/blob/master/PainterlyRendering/PainterlyRendering/result2.jpg">

>Stroke Effect
<img src="https://github.com/pooi/PainterlyRendering/blob/master/PainterlyRendering/PainterlyRendering/source1.jpg">
<img src="https://github.com/pooi/PainterlyRendering/blob/master/PainterlyRendering/PainterlyRendering/result1.jpg">
<img src="https://github.com/pooi/PainterlyRendering/blob/master/PainterlyRendering/PainterlyRendering/source3.jpg">
<img src="https://github.com/pooi/PainterlyRendering/blob/master/PainterlyRendering/PainterlyRendering/result3.jpg">
<br>

## License
```
    Copyright 2016 Taewoo You

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
```
