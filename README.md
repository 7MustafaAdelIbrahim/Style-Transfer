# Style-Transfer
Run two neural style transfer models on both the "foreground" and "background"


This innovative camera application leverages two distinct neural style transfer models to enhance the visual aesthetics of a live video feed by applying artistic effects to both the foreground and background elements. 

The first model focuses on the foreground, which typically includes the subjects or objects that are the main focus of the video. By analyzing the features and characteristics of these elements, the model applies a chosen artistic style—whether it be impressionism, cubism, or another artistic movement—transforming the way the subject appears on screen. This allows users to capture their moments not just as simple recordings, but as visually striking pieces of art that convey emotion and creativity.

Simultaneously, the second neural style transfer model operates on the background of the video feed. This model is designed to harmonize with the artistic effects applied to the foreground while ensuring that the overall composition remains cohesive and visually appealing. By utilizing advanced algorithms, it detects the contextual elements of the background and applies a complementary artistic style, creating a seamless blend that enhances the overall visual experience.

Together, these two models work in tandem to provide users with a unique and immersive experience, enabling them to create visually stunning videos in real-time. The application allows for customization, letting users choose from a variety of artistic styles and adjust parameters to achieve the desired effect. With this dual-model approach, the camera app not only transforms standard video capture into an artistic endeavor but also opens up new avenues for creative expression, making every video a potential masterpiece.

Let me know if you need any further adjustments!


main.py: file responsible for running the local backend server, loads the model (which is NOT included in the repo) and opens the cam.

model.py: file responsible for the model definition.

Neural Style Transfer.ipynb: Notebook for training a neural style transfer model from scratch, the training loop is heavily inspired from https://github.com/eriklindernoren/Fast-Neural-Style-Transfer/blob/master/train.py.

SRC: folder contains the frontend of the app (made with react).
