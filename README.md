Supplementary Material README
Overview
This README document provides detailed information about the supplementary materials included in our submission. These materials consist of raw video files and demonstration videos showing the results of tests performed using our algorithm.
File Structure
The supplementary materials are organized as follows:
		Raw Video Files: These are the original videos in raw format.
	•	File Naming Convention: [Prefix]_raw
	•	Example: 1_raw, 2_raw
		Processed Videos: These include videos processed with various methods and algorithms. The naming convention for these files is described below:
	•	Low-Light Videos with Edge Detection
	•	[Prefix]_edge: Original low-light raw videos with edge detection applied.
	•	[Prefix]_edge_SAM: Edge detected videos used as input for SAM model inference.
	•   Lightweight Low Light Edge Detection Network
	    [Prefix]_5bits_edge: Clear all the lowest 5 bits of training data for training the LLED network.
	•	Motion Estimated Low-Light Videos
	•	[Prefix]_edge_mv_SAM: Low-light videos with motion estimation applied to edge detected videos, followed by SAM model inference.
	•	Direct SAM Model Inference
	•	[Prefix]_SAM: Original videos directly processed using SAM model inference.
	•	SAM-Edge Detection Prompt Model
	•	[Prefix]_SAM-Edge Detection Prompt: Results of SAM-Edge Detection Prompt model inference.
Prefix Explanation
Each video file has a prefix that indicates the specific conditions under which the video was recorded or processed:
	•	1, 2: General identifiers for the videos.
	•	0.35lux_80: Indicates videos recorded in low light conditions of 0.35 lux and an average photon count of 80 per pixel.
	•	1.4lux_320: Indicates videos recorded in low light conditions of 1.4 lux and an average photon count of 320 per pixel.
Usage
The provided videos can be used to compare the performance of our algorithm under different conditions and processing methods. This can aid in understanding the effectiveness and versatility of our algorithm in various low-light scenarios.