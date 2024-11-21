# Video Processing With Natural Language Workflow

This workflow processes videos with input taken in the form of natural language.

## Workflow Details

- **Input Schema**:
  - `video_url`: The URL of the video to process.
  - `public_id`: The public id of the video to process.
  - `transformation_prompt`: The prompt for the transformations to apply to the file.

- **Main Steps**:
  1. Upload the video to Cloudinary:
     - Video URL and Public ID are used to upload the video to Cloudinary.
     - The video is uploaded with the resource type `video`.
  2. Generate transformations for the video:
     - Gemini 1.5 Pro reads the prompt and the input video url.
     - Generates transformations for the video based on the prompt.

## Usage

This workflow is ideal for applications that require video processing with input taken in the form of natural language.
