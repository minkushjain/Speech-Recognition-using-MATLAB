# Speech-Recognition-using-MATLAB
This is a MATLAB project for speech recognition using Co-variance technique

## Getting Started
Run the Voice_rec.m file with MATLAB software

You can add your own audio files for voice recognition.

## Introduction

Speech Recognition is the way of capturing the talked words using a gadget and converting them into a digitally stored set of words.
In the current world, there is a continually expanding need to confirm and recognize the voice of individuals automatically.
Speech recognition is basically and widely used concept for providing the security to the applications.

## Co Variation Technique

Co-variance is the measure of the deviation between two sets of random variables. It compares the two signals, by considering the provided samples and compares it with the test sample to provide the result.

Syntax for Co-variance in MATLAB is derived as r = cov(x)

r = cov(x) returns a specific covariance value to the program which can be compared with the
other signals for speech recognition.

Covariance method measures the difference between the covariance value of the sample voice
to that of the value of predefined voice and then gives the result whether accepted or not.

If the voice is recognized, it returns a electric sound, otherwise returns "Access Denied" sound if the given sample does not match.
