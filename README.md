# Image-Prompt-Injection-Demo
Image Prompt Injection is a demonstrates project about how to embed a malicious prompt within an image using steganography techniques. This malicious prompt can be later extracted by an AI system for analysis, enabling covert communication with AI models through images.

## How It Works

The script works by embedding the binary representation of the secret prompt into the least significant bits of the image pixels. This modification is imperceptible to the human eye but can be detected and extracted by AI systems during image analysis.

## Usage

1. **Install Dependencies:**
   
  `pip install opencv-python`

4. **Edit Script:**
   
  Define the path to the original image file that you want to embed the prompt into.

  Change the prompt in the script to your prompt.

4. **Run the Script:**
  `python Image_Prompt_Injection.py`


# Resources

More technical information about this attack can be found in the [technical blog](https://securaize.substack.com/p/using-image-media-to-prompt-injection)
