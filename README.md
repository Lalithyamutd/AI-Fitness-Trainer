# AI-Fitness-trainer (Watch your own workout)
This project leverages the MediaPipe library to create an AI-powered fitness trainer that tracks workout movements in real time. By monitoring body part positions and calculating angles during exercise, the model determines the count of repetitions for each movement.


# Key Features:
Real-time tracking of exercise movements using the MediaPipe library.
Detection of body part angles to determine exercise completion.
Accurate counting of exercise repetitions based on body posture.

# How it Works:
The AI model analyzes the user’s body position and movement during the workout session, calculates the angles of specific joints, and tracks the changes to accurately determine when a repetition is completed.

## Pull-Up Exercise

A pull-up is an upper-body strength exercise where the body is suspended by the hands and pulled upward. It is considered a closed-chain movement, meaning the hands are fixed in place while the body moves. During the exercise, the elbows flex and the shoulders adduct and extend, bringing the elbows toward the torso. This motion primarily targets the back, shoulders, and arms, making it an effective workout for upper-body strength.


## Push-Up Exercise



A push-up is a conditioning exercise performed in a prone position, where the body is raised and lowered by straightening and bending the arms. Throughout the movement, the back remains straight, and the body is supported by the hands and toes. This exercise primarily targets the chest, shoulders, and triceps while also engaging the core and lower body to maintain stability.



## Sit-Up Exercise

The sit-up is an abdominal endurance exercise designed to strengthen, tone, and tighten the core muscles. Unlike a crunch, sit-ups involve a greater range of motion, engaging not only the abdominal muscles but also the hip flexors, lower back, and other stabilizing muscles to improve overall core strength.




## Walking Exercise


Walking is a low-impact cardiovascular exercise that engages the legs, core, and arms to improve overall fitness. It is an excellent way to enhance endurance, increase heart rate, and boost circulation. The simple, rhythmic movement helps build strength in the lower body while providing a full-body workout with minimal strain.




## Squat Exercise




A squat is a fundamental strength training exercise where the individual lowers their hips from a standing position and then returns to an upright stance. This movement primarily targets the lower body, engaging the quadriceps, hamstrings, glutes, and calves. During the squat, the hip and knee joints bend (flex), while the ankle joint also bends (dorsiflexes) to maintain balance and proper posture.



For dynamically detecting your realtime movements using your webcam , use these commands below:
```
python main.py --exercise_type "ExerciseType"

```

