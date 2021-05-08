# How-To-Swipe
Easy tutorial for adding swipes into your Class of Fragment

<h3>1 - Create an OnSwipeTouchListener class</h3>
<h4>class has been added to the rep</h4>
<h3>2 - Make a reference to your layout</h3>
<h4>private lateinit var layout: ConstraintLayout</h4>
3-<h3>3- Use it with the layout methods</h3>
 <h4>binding.layout.setOnTouchListener(object : OnSwipeTouchListener(context) {
  
            override fun onSwipeLeft() {//DO SMT}
  
            override fun onSwipeRight(//DO SMT)
            
            override fun onSwipeUp(//DO SMT) 
            
            override fun onSwipeDown(//DO SMT)
</h4>
