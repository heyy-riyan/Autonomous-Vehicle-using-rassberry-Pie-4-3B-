# Autonomous-Vehicle-using-rassberry-Pie-4-3B-
## ABSTRACT
	An increasing safety and reducing road accidents, thereby saving lives are one of great interest in the context of Advanced Driver Assistance Systems. Apparently, among the complex and challenging tasks of future road vehicles is road lane detection or road boundaries detection. It is based on lane detection (which includes the localization of the road, the determination of the relative position between vehicle and road, and the analysis of the vehicle Silas heading direction). One of the principal approaches to detect road boundaries and lanes using vision system on the vehicle. However, lane detection is a difficult problem because of the varying road conditions that one can encounter while driving. In this paper, a vision-based lane detection approach capable of reaching real time operation with robustness to lighting change and shadows is presented. The system acquires the front view using a camera mounted on the vehicle then applying few processes in order to detect the lanes. Using a pair of hyperbolas which are fitting to the edges of the lane, those lanes are extracted using Hough transform. The proposed lane detection system can be applied on both painted and unpainted road as well as curved and straight road in different weather conditions. This approach was tested and the experimental results show that the proposed scheme was robust and fast enough for real time requirements. Eventually, a critical overview of the methods was discussed, their potential for future deployment were assist.
## INTRODUCTION
The main aim of our project is to reduce the accidents caused by disobeying the lane driving rules. The system has an objective to identify the lane marks. Its intent is to obtain secure environment and improved traffic surroundings.
	The function of the proposed system can range from displaying road line positions to the driving person on any exterior display to more convoluted application like detecting switching of lanes in the near future so that one can prevent concussions caused on the highways.
	But it is not always necessary that lane boundaries are clearly noticeable as poor road condition inadequate quantity/quality of paint used for the lane boundaries makes it hard for system to detect the lanes with accuracy and other reasons can include environment effects like shadows for things like trees or fog occurs because of invariant lightening conditions.
	So, we followed the algorithm in the project is to detect lane markings on the road by giving the videos of road as the input to the system by using computer vision technology.

## Methodology
Canny Edge Detection, Hough Line Transformation
Image thresholding
 
## Problems / Challenges
There are various challenges involving like –
1.	Variability in vehicle shape.
2.	Safety of the car.
3.	Over lighting.
4.	Sharp turned roads.
5.	Shifting lane warning.
6.	Different road environments. 
## Objectives
	We are going to concentrate on particularly these three things – 
1.	To detect both sides of the lane and maintain the vehicle inside of those lanes.
2.	To detect the curved road ahead of the vehicle.
3.	Prepare a working model that is following the above objectives using Raspberry Pi
