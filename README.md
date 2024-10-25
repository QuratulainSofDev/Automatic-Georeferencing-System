Step 1: Load reference satellite image and UAV images for viewing.
Step 2: Provide an interface to click and save pixel coordinates from UAV images.
Step 3: Compute keypoints and descriptors using feature detectors (SIFT, SURF, etc.).
Step 4: Compute the homography matrix using RANSAC to align images.
Step 5-7: Project the clicked pixel coordinates from UAV images onto the reference image and convert them to geodetic coordinates.
The project aims to demonstrate automated georeferencing using homography and local feature matching methods for UAV-based applications. Additionally, users can experiment with different detectors and descriptors, offering flexibility in performance evaluation.
