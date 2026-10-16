# EcoSmart: Smart Recycling Assistant

## 1. Project Title and Description

**EcoSmart: Smart Recycling Assistant** is an AI-powered web application that identifies waste materials from uploaded images and classifies them as recyclable, reusable, biodegradable, or hazardous. It provides smart recycling recommendations, a generative AI assistant for recycling-related queries, a digital twin dashboard to monitor virtual recycling bins and waste movement, and interactive analytics to track waste collection, recycling, reuse, and disposal, promoting efficient waste management and environmental sustainability.

## 2. Problem Statement
Improper waste disposal and incorrect waste segregation cause pollution and harm the environment. People often find it difficult to identify waste and know how to recycle, reuse, or dispose of it safely. Waste management also lacks proper monitoring of waste collection, recycling, and disposal. EcoSmart aims to solve these problems using AI to identify and classify waste, provide recycling suggestions, answer users’ questions, monitor virtual waste bins, and display waste management statistics through a dashboard.

## 3. Target Users

| User | How They Benefit |
|---|---|
| Households and Individuals | Identify waste and learn how to dispose of it correctly. |
| Students and Campus Residents | Learn about recycling and track waste during campus activities. |
| Apartment Complexes and Housing Societies | Monitor waste bins and collection schedules. |
| Municipal and Waste-Collection Staff | Track bin status and view collection records. |
| Schools and NGOs | Promote recycling awareness and environmental education. |

## 4. Existing Solutions

| Solution | What It Does | Link | Limitations |
|---|---|---|---|
| **Recycle Coach** | Provides recycling guides, collection reminders, and information about where to dispose of different items. | [Recycle Coach](https://recyclecoach.com) | Does not focus on AI-based image detection or digital twin bin visualization. |
| **Bin-e** | Uses AI-powered smart bins to automatically identify and sort waste materials. | [Bin-e](https://www.bine.world) | Requires physical smart-bin hardware, which may be costly for individuals. |

## 5. Proposed Solution and Innovation

Existing solutions provide recycling guides, require physical smart-bin hardware, or mainly focus on image-based waste classification. EcoSmart combines these features into one software-based platform without requiring any physical sensors or hardware.

1. **Photo-to-Action:** Identifies and classifies waste from uploaded images and provides step-by-step recycling, reuse, composting, or disposal instructions.

2. **Digital Twin Dashboard:** Displays virtual waste bins, estimated fill levels, collection status, and waste movement from disposal to recycling, reuse, or final disposal. Bin status is updated using user-confirmed waste scans and collection records, without physical sensors.

3. **Hazard Awareness:** Identifies hazardous waste, such as batteries, electronic waste, and chemicals, and provides safe-disposal guidance.

4. **Personalized GenAI Assistant:** Answers recycling-related questions and provides suggestions based on the user's previous waste scans.

5. **Waste Analytics:** Displays the amount of waste collected, recycled, reused, and disposed of, along with a personal recycling-rate score.

6. **Confidence-Aware Classification:** Allows users to confirm or correct waste labels when the AI model is uncertain, improving the reliability of results.

## 6. MVP Features

- **User Registration and Login:** Allow users to create accounts and log in securely.
- **AI Waste Detection and Classification:** Identify waste from uploaded images and classify it as recyclable, reusable, biodegradable, or hazardous.
- **Smart Recycling Recommendations:** Suggest how to recycle, reuse, compost, or safely dispose of waste.
- **Hazardous Waste Alerts:** Provide safety warnings and disposal guidance for batteries, electronic waste, and chemicals.
- **Digital Twin Dashboard:** Display virtual waste bins with estimated fill levels and collection status.
- **Waste Analytics:** Show charts of waste categories, recycling progress, and disposal statistics.
- **GenAI Chat Assistant:** Answer recycling-related questions and provide disposal guidance.
- **Scan History:** Store previous waste scans, classifications, and recommendations for users to review.

## 7. Suitable Technology Stack

| Layer | Technology | Why |
|---|---|---|
| Frontend | React.js + Vite, Tailwind CSS | Build a responsive and user-friendly interface quickly. |
| Charts and Dashboard | Recharts | Display waste analytics, bin gauges, and collection statistics. |
| Backend | Node.js + Express.js | Develop REST APIs and handle application logic. |
| Database | MongoDB + Mongoose | Store user accounts, waste scans, virtual bin data, and collection records. |
| Authentication | JWT + bcrypt | Provide secure login and password hashing. |
| Image Upload | Multer + Cloudinary | Handle uploaded waste images and store them online. |
| AI Waste Detection | YOLOv8 or MobileNet | Identify waste items and classify them into suitable categories. |
| AI Service | Python + FastAPI | Run the computer vision model and connect it to the main backend. |
| GenAI Assistant | Claude API or another LLM API | Answer recycling questions and provide personalized guidance. |
| Version Control | Git + GitHub | Support team collaboration, branches, pull requests, and code reviews. |
| Deployment | Vercel, Render, MongoDB Atlas | Host the frontend, backend, AI service, and database online. |



The **MERN stack** provides the foundation for developing the web application. **Python and FastAPI** support AI-based waste detection, while Recharts provides visual analytics. **MongoDB** stores waste records and virtual bin information. The application estimates bin fill levels using confirmed waste records without requiring physical sensors.


## 8. Architectural Flow Diagram

The diagram below illustrates user interaction, frontend screens, backend processing, AI-based waste classification, database operations, and the delivery of results to the user.

[EcoSmart System Architecture](images/architecture.png)

 ##  Team Members

| S.No | Name | GitHub |
|---|---|---|
| 1 | Jeevitha  | [Jeevithaa2006](https://github.com/Jeevithaa2006) |
| 2 | G K Deeksha | [deeksha0208](https://github.com/deeksha0208) |
| 3 | Janani N | [jananigowda18](https://github.com/jananigowda18) |
| 4 | Jeevitha | [Kottarysaakshi-lgtm](https://github.com/kottarysaakshi-lgtm) |

