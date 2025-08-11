# CS 590 - Advanced AI - Project 4: Ghostbusters & Bayesian Networks

**Author: Prashanna Raj Pandit**

## Overview
In this project, you will implement inference algorithms to help Pacman track and capture invisible ghosts using noisy distance readings. You will start with single, stationary ghosts and progress to hunting multiple moving ghosts using both exact and approximate inference techniques, including particle filters and joint particle filters.

This project builds on concepts in Bayesian Networks, probabilistic reasoning, and sequential state estimation.



```
Question q1
===========

*** q1) Exact inference stationary pacman observe test: 0 inference errors.
*** PASS: test_cases/q1/1-ExactObserve.test
*** q1) Exact inference stationary pacman observe test: 0 inference errors.
*** PASS: test_cases/q1/2-ExactObserve.test
*** q1) Exact inference stationary pacman observe test: 0 inference errors.
*** PASS: test_cases/q1/3-ExactObserve.test
*** q1) Exact inference stationary pacman observe test: 0 inference errors.
*** PASS: test_cases/q1/4-ExactObserve.test

### Question q1: 3/3 ###


Question q2
===========

*** q2) Exact inference elapseTime test: 0 inference errors.
*** PASS: test_cases/q2/1-ExactElapse.test
*** q2) Exact inference elapseTime test: 0 inference errors.
*** PASS: test_cases/q2/2-ExactElapse.test
*** q2) Exact inference elapseTime test: 0 inference errors.
*** PASS: test_cases/q2/3-ExactElapse.test
*** q2) Exact inference elapseTime test: 0 inference errors.
*** PASS: test_cases/q2/4-ExactElapse.test

### Question q2: 4/4 ###


Question q3
===========

*** q3) Exact inference full test: 0 inference errors.
*** PASS: test_cases/q3/1-ExactObserveElapse.test
*** q3) Exact inference full test: 0 inference errors.
*** PASS: test_cases/q3/2-ExactObserveElapse.test
[Distancer]: Switching to maze distances
Average Score: 755.7
Scores:        739, 757, 749, 749, 755, 784, 777, 735, 745, 767
Win Rate:      10/10 (1.00)
Record:        Win, Win, Win, Win, Win, Win, Win, Win, Win, Win
*** Won 10 out of 10 games. Average score: 755.700000 ***
*** smallHunt) Games won on q3 with score above 700: 10/10
*** PASS: test_cases/q3/3-gameScoreTest.test

### Question q3: 3/3 ###


Question q4
===========

*** q4) Particle filter initialization test: 0 inference errors.
*** PASS: test_cases/q4/1-ParticleObserve.test
*** q4) Particle filter observe test: 0 inference errors.
*** PASS: test_cases/q4/2-ParticleObserve.test
*** q4) Particle filter observe test: 0 inference errors.
*** PASS: test_cases/q4/3-ParticleObserve.test
*** q4) Particle filter observe test: 0 inference errors.
*** PASS: test_cases/q4/4-ParticleObserve.test
*** q4) Particle filter observe test: 0 inference errors.
*** PASS: test_cases/q4/5-ParticleObserve.test
*** q4) successfully handled all weights = 0
*** PASS: test_cases/q4/6-ParticleObserve.test
[Distancer]: Switching to maze distances
Average Score: 185.4
Scores:        182, 198, 184, 137, 181, 197, 187, 195, 198, 195
Win Rate:      10/10 (1.00)
Record:        Win, Win, Win, Win, Win, Win, Win, Win, Win, Win
*** Won 10 out of 10 games. Average score: 185.400000 ***
*** oneHunt) Games won on q4 with score above 100: 10/10
*** PASS: test_cases/q4/7-ParticleObserve.test

### Question q4: 3/3 ###


Question q5
===========

*** q5) Particle filter full test: 0 inference errors.
*** PASS: test_cases/q5/1-ParticleElapse.test
*** q5) Particle filter full test: 0 inference errors.
*** PASS: test_cases/q5/2-ParticleElapse.test
*** q5) Particle filter full test: 0 inference errors.
*** PASS: test_cases/q5/3-ParticleElapse.test
*** q5) Particle filter full test: 0 inference errors.
*** PASS: test_cases/q5/4-ParticleElapse.test
*** q5) Particle filter full test: 0 inference errors.
*** PASS: test_cases/q5/5-ParticleElapse.test
[Distancer]: Switching to maze distances
Average Score: 369.8
Scores:        359, 363, 376, 365, 386
Win Rate:      5/5 (1.00)
Record:        Win, Win, Win, Win, Win
*** Won 5 out of 5 games. Average score: 369.800000 ***
*** smallHunt) Games won on q5 with score above 300: 5/5
*** PASS: test_cases/q5/6-ParticleElapse.test

### Question q5: 4/4 ###


Question q6
===========

*** q6) Joint particle filter initialization test: 0 inference errors.
*** PASS: test_cases/q6/1-JointParticleObserve.test
*** q6) Joint particle filter elapseTime test: 0 inference errors.
*** PASS: test_cases/q6/2-JointParticleObserve.test
*** q6) Joint particle filter elapseTime test: 0 inference errors.
*** PASS: test_cases/q6/3-JointParticleObserve.test
*** q6) successfully handled all weights = 0
*** PASS: test_cases/q6/4-JointParticleObserve.test
*** q6) Joint particle filter elapseTime test: 0 inference errors.
*** PASS: test_cases/q6/5-JointParticleObserve.test

### Question q6: 4/4 ###


Question q7
===========

*** q7) Joint particle filter elapseTime test: 0 inference errors.
*** PASS: test_cases/q7/1-JointParticleElapse.test
*** q7) Joint particle filter elapseTime test: 0 inference errors.
*** PASS: test_cases/q7/2-JointParticleElapse.test
*** q7) Joint particle filter elapseTime test: 0 inference errors.
*** PASS: test_cases/q7/3-JointParticleObserveElapse.test

### Question q7: 4/4 ###


Finished at 9:01:13

Provisional grades
==================
Question q1: 3/3
Question q2: 4/4
Question q3: 3/3
Question q4: 3/3
Question q5: 4/4
Question q6: 4/4
Question q7: 4/4
------------------
Total: 25/25


                     ALL HAIL GRANDPAC.
              LONG LIVE THE GHOSTBUSTING KING.

                  ---      ----      ---
                  |  \    /  + \    /  |
                  | + \--/      \--/ + |
                  |   +     +          |
                  | +     +        +   |
                @@@@@@@@@@@@@@@@@@@@@@@@@@
              @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
            @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
            @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
            \   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
             \ /  @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
              V   \   @@@@@@@@@@@@@@@@@@@@@@@@@@@@
                   \ /  @@@@@@@@@@@@@@@@@@@@@@@@@@
                    V     @@@@@@@@@@@@@@@@@@@@@@@@
                            @@@@@@@@@@@@@@@@@@@@@@
                    /\      @@@@@@@@@@@@@@@@@@@@@@
                   /  \  @@@@@@@@@@@@@@@@@@@@@@@@@
              /\  /    @@@@@@@@@@@@@@@@@@@@@@@@@@@
             /  \ @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
            /    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
            @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
            @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
              @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
                @@@@@@@@@@@@@@@@@@@@@@@@@@
                    @@@@@@@@@@@@@@@@@@


```

### Q1 (3 pts): Exact Inference – Observation

```
python autograder.py -q q1
```
### Q2 (4 pts): Exact Inference – Time Elapse
```
python autograder.py -q q2
python autograder.py -t test_cases/q2/2-ExactElapse
```
### Q3 (3 pts): Exact Inference – Full System

```
python autograder.py -q q3
python autograder.py -q q3 --no-graphics
```
### Q4 (3 pts): Approximate Inference – Observation

```
python autograder.py -q q4
```

### Q5 (4 pts): Approximate Inference – Time Elapse

```
python autograder.py -q q5
python autograder.py -t test_cases/q5/2-ParticleElapse

```
### Q6 (4 pts): Joint Particle Filter – Observation
```
python autograder.py -q q6
```
### Q7 (4 pts): Joint Particle Filter – Time Elapse
```
python autograder.py -q q7
```
