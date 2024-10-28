# Sorting-Visualizer
The concept of visualizing algorithms lets us understand algorithms in a much better way.

This project is built using ReactJS. 
It includes visualization of few classic sorting algorithms such as: Bubble Sort, Selection Sort and Insertion Sort.

Check It Out:https://sorting-visualizer-pi-lyart.vercel.app/
# Components
It consists of 4 main Components.

1 **Header:** This component is just a text animation of the text "Sorting Visualizer".

2 **Buttons Bar:** This component includes few buttons which are used to start visualizing algorithms.

3 **Array Bar:** This component is where we visualize the algorithm using 3D Vertical Bars.

4 **Range Slider:** This component includes some range sliders through which array size and animation speed can be changed in real time.

# How does Animation Work?
While the array is being sorted, we push some indexes of the array and boolean values into animations array. 
These indexes are the indexes of the comparing element and final positioned element; and the boolean values are doSwap and isFinal which tells if the elment is being compared or is it in its final position. 
Now, this animations array is passed to another function which basically changes the color and size of the bar of the indexes in animations array. 
These changes are being done through a setTimeout() function to let the change be delayed and visible.
