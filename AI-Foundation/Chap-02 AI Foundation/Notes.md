# 📘 Artificial Intelligence (AI) Notes

## 1. What is Artificial Intelligence?
**Artificial Intelligence (AI)** is the ability of a machine to mimic **cognitive abilities** and **problem-solving capabilities** of human intelligence.  

### Human Intelligence Capabilities
- Learn new skills through observation  
- Think abstractly and reason logically  
- Communicate using language and non-verbal cues  
- Handle complex situations in real time  
- Plan both short-term and long-term goals  
- Create art, music, and inventions  

👉 **Artificial General Intelligence (AGI):**  
A machine that can mimic *all* aspects of human intelligence.  

👉 **Artificial Intelligence (AI):**  
AGI applied to **narrow objectives** (specific tasks such as classification, translation, etc.).

---

## 2. Why Do We Need AI?
The volume of data generated today is **far beyond human comprehension**.  
AI helps us make sense of it.  

### Key Reasons:
1. **Automation & Decision-Making** – handling repetitive, large-scale tasks.  
2. **Creative Support** – assisting in content creation, design, music, and problem-solving.  

---

## 3. Examples of AI Applications
- Image classification (e.g., detecting cats vs dogs)  
- Spam mail detection  
- Writing computer code  
- Predicting car prices  
- Generating content (text, images, music)  

---

## 4. AI vs ML vs DL vs DS

| Term | Definition | Example |
|------|------------|---------|
| **AI** | Broad field where machines imitate human intelligence. | Virtual assistants, autonomous vehicles. |
| **ML (Machine Learning)** | Subset of AI: algorithms learn from past data to make predictions or identify trends. | Spam filter, stock price prediction. |
| **DL (Deep Learning)** | Subset of ML: uses **neural networks** to handle complex data and large datasets. Excels in vision, speech, and NLP. | Image recognition, text generation. |
| **DS (Data Science)** | Field that combines AI/ML with statistics and domain expertise to extract insights from data. | Business analytics, customer segmentation. |

---

## 5. Types of Machine Learning

1. **Supervised Learning**  
   - Learns from labeled data.  
   - Goal: predict outcomes for new unseen data.  
   - Example: Predicting house prices from past sales data.  

2. **Unsupervised Learning**  
   - Learns hidden patterns in unlabeled data.  
   - Example: Customer segmentation, market basket analysis.  

3. **Reinforcement Learning**  
   - Learns by **trial and error** with rewards/penalties.  
   - Example: Game-playing AI (e.g., AlphaGo), robotic navigation.  

# 📘 Artificial Intelligence (AI) Notes (Part 2)

## 6. AI Domains

AI can be applied across multiple domains such as **language, audio/speech, and vision**.

---

### 🌐 Language AI
**Applications:**
- Detect language of a text  
- Extract entities (names, locations, organizations)  
- Extract key phrases  
- Understand sentiment of text  
- Classify text based on content  
- Translate text between languages  

**Generative Language Tasks:**
- Create stories, poems, or essays  
- Summarize text  
- Answer questions (Q&A systems)  
- Generate image captions  
- Complete sentences or paragraphs  
- Convert text → speech  

---

#### Text as Data
- Text is **sequential** (sentences contain ordered words).  
- Computers understand only numbers → need **tokenization** (convert words into numeric tokens).  
- Sentences vary in length → use **padding** to equalize input size.  
- To measure word similarity → use **dot product** or **cosine similarity** on **embeddings** (vector representations of words).  

---

#### Language AI Models
- **RNN (Recurrent Neural Network):** processes sequences, keeps hidden state for context.  
- **LSTM (Long Short-Term Memory):** advanced RNN with gates to retain long-term context.  
- **Transformers:** process data in parallel using **self-attention** for better context understanding (foundation for GPT, BERT, etc.).  

---

### 🎙️ Audio & Speech AI

**Applications:**
- Speech → text (speech recognition)  
- Speaker recognition  
- Voice conversion (change speaker’s voice)  
- Speech emotion recognition  
- Text → speech (speech synthesis)  

**Generative Tasks:**
- Music composition  
- Synthetic speech generation  

---

#### Audio as Data
- Audio = sequence of digitized **snapshots of sound waves**.  
- **Sampling rate:** number of times per second sound is recorded (e.g., 44.1 kHz = 44,100 samples/sec).  
- **Bit depth:** number of bits used to represent each audio sample.  
- A single sample reveals little — need many samples for meaningful features.  

---

#### Audio AI Models
- **RNN / LSTM:** handle sequential audio signals.  
- **Transformers:** parallel processing of audio for better context.  
- **Variational Autoencoders (VAEs):** for generative audio tasks.  
- **Waveform Models (e.g., WaveNet):** generate raw audio waveforms.  
- **Siamese Networks:** compare voices (e.g., speaker verification).  

---

### 👁️ Vision AI

**Applications:**
- Image classification (cat vs dog, etc.)  
- Object detection (find objects in an image)  
- Object boundary detection (segmentation)  
- Optical Character Recognition (OCR: extract text from images)  
- Counting objects  
- Facial recognition  

**Generative Tasks:**
- Generate image from text (text-to-image)  
- Generate images in specific styles  
- Enhance image resolution (super-resolution)  
- Repair damaged images (inpainting)  
- Image-to-image translation (e.g., sketch → photo)  
- Generate 3D views from 2D sketches  

---

#### Images as Data
- Images consist of **pixels** (grayscale or RGB values).  
- A single pixel is not meaningful → features emerge from groups of pixels.  

---

#### Vision AI Models
- **CNN (Convolutional Neural Networks):** learn hierarchical patterns (edges → shapes → objects).  
- **YOLO (You Only Look Once):** real-time object detection in images.  
- **GAN (Generative Adversarial Networks):** generate highly realistic images (e.g., deepfakes, AI art).  

# 📘 Artificial Intelligence (AI) Notes (Part 3)

## 7. Common AI Tasks
AI can be applied to a wide range of generic tasks across industries:

- **Anomaly Detection** → detect fraud, network intrusions, unusual patterns  
- **Recommendations** → personalized suggestions (movies, products, ads)  
- **Forecasting** → predict future outcomes (sales, weather, stock trends)  

---

## 8. Demo AI Services

### 🖼️ Vision AI Services
- Image classification  
- Object detection  
- Text detection (OCR)  
- Document detection  

### 📝 Text AI Services (OCI Examples)
- **Text Analysis:**  
  - Language detection  
  - Text classification  
  - Sentiment analysis  
  - Key phrase extraction  
  - Named Entity Recognition (NER)  
  - PII (Personally Identifiable Information) detection  

- **Text Translation:**  
  - Translate text from one language to another  

---

## 9. Summary: AI vs ML vs DL

- **Artificial Intelligence (AI):**  
  Broad concept of machines imitating human intelligence.  

- **Machine Learning (ML):**  
  Subset of AI. Algorithms learn from past data to make predictions or identify patterns.  

- **Deep Learning (DL):**  
  Subset of ML. Uses **neural networks** (multi-layered) to learn complex data representations. Excels in vision, speech, and natural language.  

---

## 10. Types of Machine Learning (Recap)
1. **Supervised Learning** → Learns from labeled data to predict outcomes.  
   - Example: Predict house prices, spam classification.  

2. **Unsupervised Learning** → Finds hidden patterns in unlabeled data.  
   - Example: Customer segmentation, clustering.  

3. **Reinforcement Learning** → Learns via trial-and-error, guided by rewards/penalties.  
   - Example: Self-driving cars, game-playing AI (AlphaGo).  

---

# ✅ Key Takeaways
- **AI** mimics human-like intelligence for specific or broad tasks.  
- **ML** enables systems to learn patterns from data.  
- **DL** pushes ML further using deep neural networks.  
- AI has **three main domains:**  
  - **Language** (translation, summarization, sentiment)  
  - **Audio/Speech** (recognition, synthesis, emotion detection)  
  - **Vision** (classification, detection, generation)  
- AI is essential due to the **scale of modern data** and its applications in **automation, creativity, and decision-making**.  
