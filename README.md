# Facial_Keypoint_Detection

Facial Keypoint recognition is one of the most famous vision challenges. Facial keypoints include points around the eyes, nose, and mouth on any face and are used in many applications, from facial tracking to emotion recognition. I have used a list of 96×96-pixel 8- bit gray level images with their corresponding (x, y) coordinates of 15 facial key points.

There are 15 key points, which represent the following elements of the face:

left_eye_center, right_eye_center, left_eye_inner_corner, left_eye_outer_corner,
right_eye_inner_corner, right_eye_outer_corner, left_eyebrow_inner_end,
left_eyebrow_outer_end, right_eyebrow_inner_end, right_eyebrow_outer_end, nose_tip,
mouth_left_corner, mouth_right_corner, mouth_center_top_lip, mouth_center_bottom_lip

Steps -

1. Accept a color image.
2. Convert the image to grayscale.
3. Detect and crop the face contained in the image.
4. Locate the facial keypoints in the cropped image.
5. Overlay the facial keypoints in the original (color, uncropped) image
