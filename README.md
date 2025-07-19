# PRODIGY_CS_02
pixel manipulation

 13 July – Project Planning & Concept Finalization
	•	Decided on building an image encryption-decryption visualizer.
	•	Selected three image types (Colored Blocks, Grayscale Gradient, Random Noise).
	•	Chose three encryption techniques:


 14 July – Image Generation Setup
	•	Wrote code to generate:
	•	Colored blocks image using numpy.
	•	Grayscale gradient using np.tile() and cv2.merge().
	•	Ensured all images resized to 100x100 for consistency.

 15 July – Encryption Functions Implementation
	•	Implemented:
	•	encrypt_xor() using np.bitwise_xor
	•	invert_colors() using 255 - pixel
	

 16 July – Decryption Logic Integration
	•	Designed decryption based on:
	•	XOR being reversible with same key.
	•	Inversion is symmetric (255 - pixel again gives original).
	•	Ensured decrypted image is visually same as original.


 17 July – Visualization & Histograms
	•	Used matplotlib to:
	•	Plot original, encrypted, and decrypted images.
	•	Overlay RGB histograms for each using ax.hist().
	•	Setup plot_image_and_hist() to avoid repetition.


 18 July – Final Cleanup
	•	Organized code into clear sections with comments.
	•	Final test runs in Colab for correctness.



 19 July – Final Execution
	•	Successfully ran full script end-to-end.
	•	Inputs tested: all 3 image types + all 3 encryption modes.
	•	Verified decryption accuracy visually & via histograms.

