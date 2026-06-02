# TEXT-AND-VIDEO-GENERATION-PIPELINE-IN-GOOGLE-COLAB


This project develops a pipeline to generate short, animated video sequences from a single static image guided by textual prompts. The methodology utilizes a multi-stage process:
 * **Object Segmentation:** The Segment Anything Model (SAM) is used to isolate the primary subject from the initial image.
 * **Frame Generation:** Stable Diffusion's image-to-image functionality generates a sequence of frames based on evolving text prompts to create a narrative arc.
 * **Temporal Smoothing:** Real-Time Intermediate Flow Estimation (RIFE) interpolates intermediate frames to reduce jitter and ensure fluid, visually coherent video transitions.
