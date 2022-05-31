# The-layout-editor
A relative layout is a view grouping in which each view is positioned and aligned relative to other views within the group.In this particular task we learn how to build a layout with Relative layout.
<br>
<br>
<img src="/Screenshots/linear.gif" width="250" height="350"/>
<br>
<br>
Layout editor in relative layout in landscape
<br><br>
<img src="/Screenshots/layout_relativeland.png" width="550" height="350"/>
<br>
<br>
Layout editor in relative layout x-large(tablet version)
<br><br>
<img src="/Screenshots/tablet.png" width="550" height="350"/>
<br>
<br>
<b>Layout editor in linear layout</b>
<br>
linear layout is a ViewGoup which arranges its collection of views in a horizontal or vertical row.A linear layout is one of the most common layouts because it is imple and fast. it is often used within another view group to arrange UI elements horizontally or vertically.
<br>
<br>
<img src="/Screenshots/layout_relativex-large.png"  width="250" height="450"/>
<br><br>

<b>Challenges</b>
The layout editor challenger is to accommodate horizontal (landscape) orientation for a tablet, you can center the Button elements in activity_main.xml (xlarge) so that they appear as shown in the figure below.
<img src="/Screenshots/linear.png" width="350" height="250"/>
<br>
<br>
Layout editor homework

Align the Toast and Count Button elements along the left side of the show_count TextView that shows "0". Include a third Button called Zero that appears between the Toast and Count Button elements. Distribute the Button elements vertically between the top and bottom of the show_count TextView. Set the Zero Button to initially have a gray background.Make the Zero Button change the value in the show_count TextView to 0. Update the click handler for the Count Button so that it changes its own background color, depending on whether the new count is odd or even. Update the click handler for the Count Button to set the background color for the Zero Button to something other than gray to show it is now active. Hint: You can use findViewById in this case. Update the click handler for the Zero Button to reset the color to gray, so that it is gray when the count is zero.
<img src="/Screenshots/linearh.gif" width="350" height="250"/>

<br>
<img src="/Screenshots/Layoutconstrainthomework_land.png" width="550" height="350"/>

<br>
<br>
Question 1

Which two layout constraint attributes on the Zero Button position it vertically equal distance between the other two Button elements?
-> android:layout_marginBottom="8dp"
-> android:layout_marginTop="8dp"

Question 2

Which layout constraint attribute on the Zero Button positions it horizontally in alignment with the other two Button elements?
-> app:layout_constraintLeft_toLeftOf="parent"

Question 3

What is the correct signature for a method used with the android:onClick XML attribute?
-> public void callMethod(View view)

Question 4

The click handler for the Count Button starts with the following method signature:
public void countUp(View view)
Which of the following techniques is more efficient to use within this handler to change the Button element's background color?
-> Use the view parameter that is passed to the click handler with setBackgroundColor(): view.setBackgroundColor()
