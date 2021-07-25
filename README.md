# PointerAnalysisTool
Pointer Analysis tool is a flask web-app that provides insights based on your academic performance with prediction for your next semester result built with 'LSTM'(a R-CNN based solution).

# Steps to get started
- Download the repository.
- Unzip the folder.
- Install required dependacies from [requirements.txt].
- Open cmd and run command ```python app.py```.

#### H4 1) Home Page
![Enter the basic details](https://user-images.githubusercontent.com/31877827/126903746-d1bf1915-ffcb-446f-9b94-fee23486f86f.png)

#### H4 2) Displaying Details
![Displaying details entered](https://user-images.githubusercontent.com/31877827/126903810-73413471-a0db-4783-a53a-794bd9a7917b.png)

#### H4 3) Enter SGPA of every Semester completed
![Entering SGPA of every Semester](https://user-images.githubusercontent.com/31877827/126903893-a9bb0a43-0db6-4743-a827-49c5d12be529.png)

SGPA(Semester Grade Point Average) of every semester needs to be entered with a space, as mentioned in the place holder. If the checkbox for Diploma Student is on then by default the first 2 semesters in the list will be set to 0
I have entered the SGPA of my last 7 semesters.

#### H4 4) Displaying Remarks and Summary of Academic Performance
![Displaying Remarks of Performance](https://user-images.githubusercontent.com/31877827/126904089-2cb17fb9-93ee-48d6-bdc5-851c524078b5.png)

![Summary of Performance](https://user-images.githubusercontent.com/31877827/126904293-4a707889-d9aa-4221-ab4f-c784e26cd6e5.png)

#### H4 5) Performance Graph
![Performace Graph (Semester vs SGPA)](https://user-images.githubusercontent.com/31877827/126904330-182cd935-da18-41f3-a733-a05f19c5b1af.png)

#### H4 6) Performance Review
![Performance Review of every semester](https://user-images.githubusercontent.com/31877827/126904351-8b20d382-da5b-4890-a7ba-659a8d9fae1d.png)

#### H4 7) Desired Score and Result
![Entering desired score](https://user-images.githubusercontent.com/31877827/126904425-60b04ff0-784c-4236-b44c-4d2775652f00.png)

I desire to have a CGPA(Cumulative Grade Pointer Average) of 7.25 at end of my course this function returns the result if I can complete my course with the desired CGPA and how much I need to score in my remaining semesters, if not then it returns the most realistic score I can achieve.


![Expected Score](https://user-images.githubusercontent.com/31877827/126904556-7f34ce56-45f2-4961-9121-b21d36a64708.png)

Let's test with an unrealistic score, I enter CGPA - 10

![Displays the realistic score](https://user-images.githubusercontent.com/31877827/126904629-123f3b88-d110-4986-8eb7-e17351f3e61a.png)

#### H4 8) Prediction Feature

![Final Feature](https://user-images.githubusercontent.com/31877827/126905507-f804eb5b-e0db-4ab7-9f5d-d135e6c4943f.png)

Prediction result
![LSTM Preiction Result](https://user-images.githubusercontent.com/31877827/126906216-a2448c9c-ac3d-4a3b-ae20-5deda588d214.png)

Haha...as per my performance the model predicts I will score a perfect 10 in my next semester.











































[requirements.txt]: https://github.com/glenveigas437/PointerAnalysisTool/blob/main/requirements.txt
