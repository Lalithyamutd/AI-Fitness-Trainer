# AI-Fitness-trainer (Watch your own workout)
This project leverages the MediaPipe library to create an AI-powered fitness trainer that tracks workout movements in real time. By monitoring body part positions and calculating angles during exercise, the model determines the count of repetitions for each movement.


# Key Features:
Real-time tracking of exercise movements using the MediaPipe library.
Detection of body part angles to determine exercise completion.
Accurate counting of exercise repetitions based on body posture.

# How it Works:
The AI model analyzes the user’s body position and movement during the workout session, calculates the angles of specific joints, and tracks the changes to accurately determine when a repetition is completed.

## Pull-Up Exercise

A pull-up is an upper-body strength exercise. The pull-up is a closed-chain movement where the body is suspended by the hands and pulls up.As this happens, the elbows flex and the shoulders adduct and extend to bring the elbows to the torso.

```
python main.py -t pull-up -vs videos/pull-up.mp4
```


## Push-Up Exercise



A push-up is a conditioning exercise performed in a prone position by raising and lowering the body with the straightening and bending of the arms while keeping the back straight and supporting the body on the hands and toes.

```
python main.py -t push-up -vs videos/push-up.mp4
```


## Sit-Up Exercise


The sit-up is an abdominal endurance training exercise to strengthen, tighten and tone the abdominal muscles. It is similar to a crunch, but sit-ups have a fuller range of motion and condition additional muscles.
```
python main.py -t sit-up -vs videos/sit-up.mp4
```



## Walking Exercise



```
python main.py -t walk -vs videos/walk.mp4
```



## Squat Exercise




A squat is a strength exercise in which the trainee lowers their hips from a standing position and then stands back up. During the descent of a squat, the hip and knee joints flex while the ankle joint dorsiflexes.

```
python main.py -t squat -vs videos/squat.mp4
```

For dynamically detecting your realtime movements using your webcam , use these commands below:
```
python main.py -t sit-up
# or python main.py -t pull-up
# or python main.py -t push-up
# or python main.py -t squat
# or python main.py -t walk
```

