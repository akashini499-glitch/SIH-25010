# Smart India Hackathon Workshop
# Date:30.09.2025
## Register Number:25016886
## Name:AKASHINI V
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
Pest and disease detection via image uploads and instant feedback.

## Technical Approach
A robust technical approach for pest and disease detection via image uploads and instant feedback involves deploying AI-powered image recognition within a user-friendly mobile application. This generally includes the following components and workflow:

Key Components:
A multilingual mobile app for farmers to upload images or scan leaves in real-time.

Backend cloud or edge server with pre-trained deep learning models (such as ResNet50, MobileNet, or more advanced Convolutional Neural Networks) for image detection/classification.

Access to curated datasets of healthy and diseased crop images (sources include PlantVillage, PlantDoc, etc.) for model training and ongoing improvement.

Data augmentation and preprocessing pipelines to handle variable image quality and field conditions.
Flowchart:
1. Farmer uses mobile app (multilingual UI)
      ↓
2. Capture or scan leaf image
      ↓
3. Image preprocessing & augmentation
      ↓
4. Send to backend (cloud or edge server)
      ↓
5. Run deep learning model (e.g., ResNet50, MobileNet)
      ↓
6. Get disease classification & confidence
      ↓
7. Show results + advice in local language
      ↓
8. (Optional) Upload image for retraining
      ↓
9. Model updated using curated datasets (PlantVillage, PlantDoc, etc.)


## Feasibility and Viability
Feasibility:
The proposed system is technically feasible using existing AI models, mobile technologies, and cloud/edge computing to deliver accurate, real-time disease detection. Multilingual and voice-enabled interfaces ensure accessibility for low-literacy farmers, even in low-connectivity rural areas.

Viability:
Connectivity issues in rural areas may limit real-time app usage, which can be mitigated with offline features. Ensuring high model accuracy requires continuous data collection and validation to prevent misdiagnosis and maintain user trust.

Solutions to overcome:
Develop offline-capable app features (e.g., image-based disease detection via on-device models).
Deploy lightweight versions of the AI model on mobile devices or local edge devices (e.g., Raspberry Pi).
Enable basic interaction (alerts, recommendations) via SMS or USSD for feature phones.

## Impact and Benefits
Impact: Early and accurate detection enables timely intervention.

Benefit: Prevents disease spread and crop loss, leading to higher productivity and food security.
## Research and References
PlantVillage dataset — a widely used benchmark for crop disease image classification tasks.

PlantDoc, PlantWild — more diverse datasets useful especially for real‑world variability (lighting, background, etc.).

PlantInfoCMS system — an image collection + annotation + inspection pipeline that ensures higher data quality.
