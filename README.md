# tutorial9IntroProg2016
week 9 tutorial solutions. Python Jython manipulating images.


# *************************** Question/Activity 1 ******************************
# Attempt all of the questions for this week. I.e. if you cannot finish the
# program below, move on to the others without leaving them blank.
# Note: If you are stuck with this at any point, please email me and ask.
#
# In this activity, you will create a "luminance (grey) histogram" for a picture
# chosen by the user. A luminance histogram is created by counting how many
# pixels are there for each level of luminance and then by drawing a chart (typically
# a bar chart) showing "how popular" each luminance value was in the image.
# Please check Google Images for examples.
# There are many ways to approach this. Here's the suggested approach (feel free to
# follow your own as long as yours is functionally the same or better):
# 1. Create a list of 256 integers as follows:
#    histogramData=[0]*256
# 2. Go through each pixel of the image and at each pixel:
#   2.1: Calculate the luminance "lum" of that pixel (i.e. the average of RGB
#        vaues). This value would be an integer between 0-255.
#   2.2: Increment the value in the list at position "lum" by 1.
# 3. The previous step will generate the data necessary for the histogram. You
#    must now create an empty image for the histogram. It should be 256 pixels
#    wide as there are only 256 unique levels. The height of the histogram should
#    be tall enough to fit the largest value in the histogramData list. You can
#    manually estimate what the height at first but later you can think about
#    making the height dynamic to different pictures' histograms.
# 4. Go through the histogram list and for each item, draw a line (i.e. a bar
#    in the bar chart) whose height corresponds to the value of the item
#    in the list. 
#    The lines should start from the bottom of the image. The x coordinates of
#    each line will correspond to the list element's position. E.g. list item at
#    position zero will have its line drawn at x zero in the histogram, etc.
# Optional: Can you extend this to show a RGB histogram?
# Write your code/answer immediately below:




# *************************** Question/Activity 2 ******************************
# Using 'while' loops instead of 'for' loops, attempt question 5.8 from the link
# below (login necessary):
# https://equella.rmit.edu.au/rmit/file/0dd40e51-d2e4-4c42-9953-78a8da7814a4/1/130124_1_001.pdf
# Hint: Please refer to recent tutorial recordings and solutions on how to use
#       'while' loops and ask Yongli if you still don't know.
# Write your code/answer immediately below:





# *************************** Question/Activity 3 ******************************
# Using 'while' loops instead of 'for' loops, attempt question 5.9 from the link
# below (login necessary):
# https://equella.rmit.edu.au/rmit/file/0dd40e51-d2e4-4c42-9953-78a8da7814a4/1/130124_1_001.pdf
# Hint: Please refer to recent tutorial recordings and solutions on how to use
#       'while' loops and ask Yongli if you still don't know.
# Write your code/answer immediately below:




# *************************** Question/Activity 4 ******************************
# This is a reflective learning exercise. Looking at all the programming problems
# that you have tackled so far, give brief details on:

# a) The one that you felt you learned the most from at the time:
# (Write below)


# b) The one that you feel you could make the biggest improvement on, if attempted again:
# (Write below)





# ******************************************************************************
# **************************** End of Document *********************************
# ******************************************************************************

