# ACM Alexandria Student Chapter "TheXCourse: Android"
* A repository for projects and skeletons for ACM Alexandria Student Chapter's "The X Course:Android".

* This work was done during my time working as an Android Instructor for ACM Alexandria Student Chapter.

## Assignments
### Assignment 1: GeoQuiz
Originally from "Android Programming- The Big Nerd Ranch Guide" Chapter 1.

The application you are going to create is called GeoQuiz. GeoQuiz tests the user’s knowledge of
geography. The user presses True or False to answer the question on screen, and GeoQuiz provides
instant feedback.

### Assignment 2: The Cheating GeoQuiz
Originally from "Android Programming- The Big Nerd Ranch Guide" Chapter 5. 

You will add a second activity to GeoQuiz. An activity controls a screen of information,
and this activity will add a second screen that offers users a chance to see the answer to the current
question.

Why is this a good Android programming exercise? You will learn how to:

• Create a new activity and a new layout for it.

• Start an activity from another activity. Starting an activity means asking the OS to create an
activity instance and call its onCreate(Bundle) method.

• Pass data between the parent (starting) activity and the child (started) activity.

• Also, we add Lifecycle Callbacks and use Logcat to better understand the activity lifecycle.

### Assignment 3: The Cheat-Aware GeoQuiz
In this version of GeoQuiz, we do modifications in order to receive updates from the Cheating Screen in the Quiz Screen about whether the user has used his cheating opportunity or not. See ? A cheat-aware GeoQuiz indeed.

• We do this by learning about passing data from child activity to parent activity when we press the back button to navigate back to the parent. 

• We also introduce a bug during the process "Configuration Changes".

• We use an appropriate solution for it "InstanceState".

