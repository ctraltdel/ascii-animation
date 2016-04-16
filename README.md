# ascii-animation

An element to provide a way to animate ascii text. Animation is keyframe based. 

A sequence of keyframes are used with a selector property indicating the frame should display when the duration is that % out of 100.

Example:
```
    <ascii-animation duration="1" autoplay>
      <ascii-animation-keyframe name="smiley" selector="0">:)</ascii-animation-keyframe>
      <ascii-animation-keyframe name="meh" selector="50">:|</ascii-animation-keyframe>
      <ascii-animation-keyframe name="frownie" selector="100">:(</ascii-animation-keyframe>
    </ascii-animation>
```