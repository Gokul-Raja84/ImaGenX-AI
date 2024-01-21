
# ImaGenX-AI

A user-friendly web application that leverages Google's Most Advanced Text To Image Model through the Imagen 2 API. Users can input prompts, and the application fetches and displays images generated based on those prompts.

## Explore Vertex AI

1. **Create a Google Cloud Account:**
   - Go to [Google Cloud](https://cloud.google.com/) and register for a free account.

2. **Access Vertex AI Dashboard:**
   - Visit the [Vertex AI Dashboard](https://console.cloud.google.com/vertex-ai) in the Google Cloud Console.
   
3. **Navigate to Model Garden:**
   - Click on "Model Garden" on the left-hand menu.

4. **Filter and Select Imagen:**
   - Use the filters to select "Vision" and click on "Imagen" for Image Generation and Editing.

5. **Retrieve API Information:**
   - Scroll down to find the relevant API information.

Sample AI generated Images from ImaGenX-AI using Google's Imagen 2 API 

![an-expansive-wheat-field-bathed-in-the-moonlight-upscaled (1)](https://github.com/Gokul-Raja84/ImaGenX-AI/assets/106546785/c4cbc75e-9e71-4091-a89c-931176c62ae4)
![a-panoramic-view-of-a-mountain-range-under-a-star-upscaled](https://github.com/Gokul-Raja84/ImaGenX-AI/assets/106546785/5c483f5d-67c9-4543-8a39-076cfd3a41d6)
![a-tropical-paradise-with-palm-trees-and-a-blue-o-upscaled](https://github.com/Gokul-Raja84/ImaGenX-AI/assets/106546785/3de9d1ca-3917-4026-9f99-975fe57a3347)



## How to Run ImaGenX Locally

1. **Clone the Repository:**
   - Clone the repository to your local machine and navigate to the project folder.
     ```bash
     git clone https://github.com/Gokul-Raja84/ImaGenX-AI.git
     cd ImaGenX-AI
     ```

2. **Install Dependencies:**
   - Run the following command to install project dependencies.
     ```bash
     npm install
     ```

3. **Set Environment Variables:**
   - Create a `.env` file in the project's root folder.

   - On Google Cloud Console:
     - Ensure you are on the correct project.
     - Enable Vertex AI in the "APIs & Services" section.

   - In the `.env` file:
     ```env
     VITE_GOOGLE_PROJECT_ID=your-project-id
     VITE_GCLOUD_AUTH_TOKEN=your-access-token
     ```

   - Install gcloud CLI and run:
     ```bash
     gcloud auth login
     gcloud auth print-access-token
     ```

4. **Run the Application:**
   - Start the application locally.
     ```bash
     npm run dev
     ```

## Possible Issues and Solutions

- **Token Expiry:**
  - The gcloud access token is valid for only 1 hour. Regenerate it and update the `.env` file.
    ```bash
    gcloud auth print-access-token
    ```

- **Prompt Compliance:**
  - Some prompts may not comply with Google's laws, leading to errors. Check the browser console for details.

## Acknowledgments
Feel Free to Explore and Experiment, I encourage you to explore the project, expriment with different approaches, and contribute to improving visualizations, and UI. Your contributions and innovative ideas can be pivotal in advancing this project's effectiveness and generating valuable outcomes


## Contact
For feedback, suggestions, or collaborations, feel free to connect with me :

Contact Me - Gokul Raja

Email - gokulraja840@gmail.com

Feel free to reach out if you encounter any issues or have further questions. Thank you!
