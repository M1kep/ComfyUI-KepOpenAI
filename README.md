# ComfyUI-KepOpenAI

## Overview
ComfyUI-KepOpenAI is a user-friendly node that serves as an interface to the GPT-4 with Vision (GPT-4V) API. This integration facilitates the processing of images coupled with text prompts, leveraging the capabilities of the OpenAI API to generate text completions that are contextually relevant to the provided inputs.

## Features
- Accepts both an image and a text prompt as input.
- Integrates seamlessly with the OpenAI GPT-4V API to provide intelligent text completions.
- Requires an OpenAI API key, which should be securely stored and provided as an environment variable.

## Configuration
To utilize this node, you must set the `OPEN_AI_API_KEY` environment variable with your OpenAI API key. This ensures that the API is accessible and requests are authenticated properly.
