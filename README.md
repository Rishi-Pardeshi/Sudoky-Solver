# Introduction
It is a sudoku solver made using python. It can detect and solve sudoku from an image. It uses deep-learning to predict numbers in sudoku cells.
# Dependencies
> Cvzone<br>
> Numpy<br>
> Opencv_python<br>
> Tensorflow<br>
# How to use ?
Clone the git repository using this command,
> git clone https://github.com/Rishi-Pardeshi/Sudoky-Solver.git

Install all dependencies into your computer
> pip install -r path/to/Sudoku_Solver/requirements.txt

Thats all, now you can simply use the sudoku solver by typing
> python main.py path/to/sudoku_image

Or you can run an example by typing
> python example.py

# How It Works
- First the program do preprocessing of image.
- It finds all contours in an image.
- Next it finds sudoku in an image.
- Then the function uses wrap prespective if the sudoku is not parallel or in irregular shape.
- Next it detect all digits in each cell of sudoku and display them on an blank image.
- Next the algorithm solves sudoku and display solved numbers in blank screen.
- At last but not least it rewrap prespective of solved sudoku and overlay it on orignal image.
### Example<br>
![Example](https://user-images.githubusercontent.com/98802415/153587621-3d66150e-6208-4381-b209-34d39a5f3c8b.png)
# Future Updates.
This program can only solve sudoku's on an image, but we are working on the program to solve sudoku in real-time.
