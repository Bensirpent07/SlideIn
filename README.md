V1.0.0 Release Notes: The main thing you must remember is that if you want to have an animation that starts off unseen, you must give the tag you want animated a <code>display: none</code> in CSS.
<h1>Methods</h1>
<em>All values are default values that you can change.</em>
<h3>.slideInLeft</h3>
<b>Description: Slide in from the left side.</b>
Usage: <code>$('tag').slideInLeft({speed:400, distance: '100px', startOpacity: 0, opacitySpeed: 400});</code>
Run down of the settings:
<code>speed</code>: How fast the animation animates.
<code>distance</code>: How far away the animation begins.
<code>startOpacity</code>: How opaque the tag starts when the animation starts.
<code>opacitySpeed</code>: How fast the opacity changes during the animation.

<h3>.slideInRight</h3>
<b>Description: Slide in from the right side.</b>
Usage: <code>$('tag').slideInRight({speed: 400, distance: '100px', startOpacity: 0, opacitySpeed: 400});</code>
Run down of the settings:
<code>speed</code>: How fast the animation animates.
<code>distance</code>: How far away the animation begins.
<code>startOpacity</code>: How opaque the tag starts when the animation starts.
<code>opacitySpeed</code>: How fast the opacity changes during the animation.

<h3>.slideInDown</h3>
<b>Description: Slide in from the top.</b>
Usage: <code>$('tag').slideInDown({speed: 400, distance: '100px', startOpacity: 0, opacitySpeed: 400, comeDown: true, comeUp: null});</code>
Run down of the settings:
<code>speed</code>: How fast the animation animates.
<code>distance</code>: How far away the animation begins.
<code>startOpacity</code>: How opaque the tag starts when the animation starts.
<code>opacitySpeed</code>: How fast the opacity changes during the animation.
<code>comeDown</code>: Tells the animation to come from the top.
<code>comeUp</code>: Tells the animation to come from the bottom.

<h3>.slideInUp</h3>
<b>Description: Slide in from the bottom.</b>
Usage: <code>$('tag').slideInUp({speed: 400, distance: '100px', startOpacity: 0, opacitySpeed: 400, comeDown: true, comeUp: null});</code>
Run down of the settings:
<code>speed</code>: How fast the animation animates.
<code>distance</code>: How far away the animation begins.
<code>startOpacity</code>: How opaque the tag starts when the animation starts.
<code>opacitySpeed</code>: How fast the opacity changes during the animation.
<code>comeDown</code>: Tells the animation to come from the top.
<code>comeUp</code>: Tells the animation to come from the bottom.

<h3>.slideInDiagonal</h3>
<b>Description: Slide in from any corner.</b>
Usage: <code>$('tag').slideInDiagonal({speed: 400, distance: '100px', startOpacity: 0, opacitySpeed: 400, left: true, right: null comeDown: null, comeUp: null});</code>
<font style="color: red">Note:</font> You must choose either <code>comeDown</code> or <code>comeUp</code> for the animation to run. You can look at the example page to see an example of a diagonal animation.
Run down of the settings:
<code>speed</code>: How fast the animation animates.
<code>distance</code>: How far away the animation begins.
<code>startOpacity</code>: How opaque the tag starts when the animation starts.
<code>opacitySpeed</code>: How fast the opacity changes during the animation.
<code>left</code>: Tells the animation to come from the left portion of the tag.
<code>right</code>: Tells the animation to come from the right portion of the tag.
<code>comeDown</code>: Tells the animation to come from the top.
<code>comeUp</code>: Tells the animation to come from the bottom.
