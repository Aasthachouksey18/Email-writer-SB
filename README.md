# ✉️ AI Email Writer - Spring Boot Assistant

A robust backend service designed to automate professional email generation using **Java 21**, **Spring Boot 3.x**, and **Google Gemini AI**. This project leverages the power of Large Language Models (LLMs) to help users draft emails with specific tones and contexts.

## 🚀 Key Features
* **AI-Powered Generation:** Instantly creates email drafts based on user input topics.
* **Customizable Tones:** Supports different communication styles (Formal, Casual, Urgent).
* **Modern AI Integration:** Uses the latest **Spring AI** framework for seamless communication with Google Gemini.
* **RESTful API:** Clean and documented endpoints for easy backend integration.

## 🛠️ Tech Stack
* **Language:** Java 21 (Utilizing Virtual Threads & Modern Syntax)
* **Framework:** Spring Boot 3.x
* **AI Engine:** Google Gemini API
* **Integration:** Spring AI
* **Build Tool:** Maven
* **API Testing:** Postman

## 📈 Project Status: 🚧 Work in Progress
I am currently focusing on:
1.  **Prompt Engineering:** Refining AI prompts for more accurate email subjects and body structure.
2.  **Scalability:** Implementing **Java 21 Virtual Threads** to handle high-concurrency requests efficiently.
3.  **Exception Handling:** Adding global exception handling for robust API responses.

## ⚙️ How to Get Started

### Prerequisites
* JDK 21 or higher
* Maven 3.6+
* Google Gemini API Key

### Installation & Setup
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Aasthachouksey18/Email-writer-SB.git](https://github.com/Aasthachouksey18/Email-writer-SB.git)
    ```
2.  **Configure API Key:**
    Open `src/main/resources/application.properties` and add your key:
    ```properties
    spring.ai.gemini.api-key=YOUR_API_KEY_HERE
    ```
3.  **Build and Run:**
    ```bash
    mvn spring-boot:run
    ```

---
Developed with ❤️ by [Aastha Chouksey](https://linkedin.com/in/aastha-chouksey)
