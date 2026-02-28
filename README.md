# Agrex.AI – Data Science Portfolio and Projects

Welcome to **Agrex.AI**, a showcase of advanced data‑science projects by **Abdul Zaid**.  In addition to the original transistor‑detection code in this repository, this page provides an overview of Abdul’s professional experience, core competencies, technical skills, and selected projects.  Together, they highlight a track record of delivering AI‑driven solutions and scalable data platforms across diverse industries.

## About Abdul Zaid

Abdul is a results‑driven data scientist with more than 2.5 years of experience architecting enterprise‑grade data platforms and designing AI solutions.  He is currently a **Data Scientist at Softsensor AI** where he leads cross‑functional teams to deliver AI‑powered analytics and decision automation solutions【621367434764805†L1-L31】.  His expertise spans predictive analytics, machine learning, generative AI, big‑data engineering, and business intelligence.  Abdul is recognized for his mentorship, having conducted over 20 workshops and seminars nationwide to foster AI skill development【621367434764805†L16-L23】.

### Core Competencies

- **Enterprise Data Platform Architecture** – Designing unified data platforms that integrate disparate systems into scalable analytics pipelines【621367434764805†L32-L41】.  
- **AI & Generative Models** – Building generative AI and large‑language‑model (LLM) solutions, including retrieval‑augmented generation (RAG) and agentic AI workflows【621367434764805†L54-L67】.  
- **Predictive Analytics & Forecasting** – Developing time‑series models and multivariate forecasting solutions to optimize KPIs, pricing, and inventory【621367434764805†L132-L144】【621367434764805†L168-L180】.  
- **Big Data Engineering** – Proficient in PySpark, Microsoft Fabric, AWS Glue and Redshift to process large datasets【621367434764805†L54-L70】.  
- **Business Intelligence & Visualization** – Creating interactive dashboards with Tableau, Power BI and Python to turn complex data into actionable insights【621367434764805†L105-L108】.  
- **Machine Learning & Computer Vision** – Applying deep‑learning and computer‑vision techniques for surveillance, safety compliance and operational monitoring【621367434764805†L16-L18】【621367434764805†L168-L168】.

### Technical Skills

**Programming:** Python (TensorFlow, PyTorch, Hugging Face, LangChain), Flask/Django, Qiskit.  
**Big‑Data & Cloud:** PySpark, Microsoft Fabric, AWS Glue, Redshift, Azure, AWS Sagemaker, AWS Lambda, AWS S3/EC2, Lakehouse/Warehouse/Semantic layers【621367434764805†L54-L70】.  
**ML & AI:** Machine learning, time‑series analysis, computer vision, NLP, generative AI, RAG, prompt engineering, fine tuning, transfer learning【621367434764805†L54-L67】.  
**Data Management:** SQL, Snowflake, ETL/ELT, data warehousing and data mesh【621367434764805†L71-L73】.  
**Visualization:** Tableau, Power BI, Pandas, NumPy【621367434764805†L73-L74】.

### Education & Certifications

- **Master of Data Science** – Christ University, Bengaluru (2023)【621367434764805†L85-L88】.  
- **Bachelor of Science (Physics Hons.)** – Jamia Millia Islamia University, New Delhi (2020)【621367434764805†L88-L90】.  
- Certifications: Advanced Certification in Data Science, IBM AI Professional, Tableau Certification, MBA in Marketing & Business Strategy, Python for Data Science (IBM)【621367434764805†L75-L83】.

### Professional Experience

**Data Scientist – Softsensor AI (March 2023 – Present)**【621367434764805†L92-L100】  
- Architected a unified enterprise data platform using AWS and Microsoft Fabric, integrating multiple systems (Protel, IDS, Touche, SAP, Alif) into a central warehouse【621367434764805†L97-L103】.  
- Designed and managed a centralized data warehouse with AWS S3/Redshift and PySpark for high‑performance processing【621367434764805†L99-L103】.  
- Created and refined critical business KPIs using Python and SQL; built interactive Tableau/Power BI dashboards that improved forecasting accuracy and decision speed【621367434764805†L105-L108】.  
- Advised on AI strategy by leveraging computer vision, LLMs and predictive analytics for surveillance and demand forecasting【621367434764805†L109-L112】.  
- Developed an AI‑driven co‑pilot within Microsoft Fabric that enabled self‑service analytics and real‑time decision intelligence【621367434764805†L113-L115】.

## Selected Projects

- **Enterprise Data Platform for Hospitality (Lemon Tree Hotels)** – Designed and deployed an enterprise‑wide data warehouse following the Medallion architecture; delivered Power BI dashboards that improved forecasting of occupancy, average room rate (ARR) and booking nights by 15%【621367434764805†L134-L140】.  
- **Workforce Planning (Aviation)** – Built predictive models to forecast recruitment, retirement and promotion trends, enabling data‑driven manpower allocation and improving planning accuracy by over 20%【621367434764805†L142-L145】.  
- **Custom Agentic AI Solutions** – Developed an LLM‑powered AI assistant with retrieval‑augmented generation to automate consulting workflows; reduced report preparation time by 40% and enhanced recommendation accuracy【621367434764805†L147-L151】.  
- **Unified Data Platform with Microsoft Fabric & AI Dashboards** – Architected a pipeline integrating lakehouse, warehouse and semantic layers for scalable analytics; enabled AI‑powered dashboards and ad‑hoc queries, reducing decision‑making turnaround time by 35%【621367434764805†L154-L157】.  
- **Predictive Pricing Model – Soil Dumping Optimization** – Created a rule‑based algorithm to optimize transport routes, achieving up to 18% savings in fuel consumption【621367434764805†L159-L163】.  
- **AI‑Powered CCTV Surveillance System** – Led development of a deep learning–based system for real‑time intrusion detection, helmet compliance and queue monitoring; improved incident detection speed by 50% and reduced manual monitoring requirements by 35%【621367434764805†L166-L168】.  
- **Automated Technical Assessment Platform (LLM‑Based)** – Built an AI‑driven assessment generator with rubric‑based scoring and CV‑to‑test mapping; automated evaluation workflows and reduced candidate screening time by 60%【621367434764805†L171-L174】.  
- **Inventory Forecasting – Jewellery Retail** – Designed a multivariate time‑series model to predict demand and prevent overstocking; reduced excess stock by 22%【621367434764805†L176-L180】.  
- **Proctor AI – Mock Interview Evaluator** – Developed an NLP‑based engine that provided real‑time scoring on communication, content and confidence, reducing manual evaluation workload by 70%【621367434764805†L182-L186】.

## Repository Projects

### Transistor Detection (Agrex.AI)

This repository started as a Jupyter notebook for detecting transistors in images using OpenCV.  The updated version now includes a standalone Python script (`enhanced_transistor_detection.py`) that implements the detection pipeline as modular functions and provides a command‑line interface.  Key features:

1. **Image Processing Pipeline** – Convert images to grayscale, apply Gaussian blur, thresholding (Otsu’s method by default) and morphological operations to isolate transistor‑like regions.  
2. **Contour Detection** – Find contours in the binary image and draw bounding boxes around candidate transistors.  
3. **Command‑Line Interface** – Specify input images, optional cropping coordinates and output paths via command‑line arguments.  
4. **Reusable Functions** – The detection logic is encapsulated in functions (`detect_transistors` and `parse_crop_arg`) so you can import and reuse them in other projects.

### Usage

1. Clone this repository and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the enhanced script on your image (provide optional cropping rectangle and output path):
   ```bash
   python enhanced_transistor_detection.py path/to/image.jpg --crop 100 200 800 1200 --save result.jpg
   ```
3. The script prints the number of detected transistors and saves the annotated image to the specified output file (or displays a window if `--save` is omitted).

For more details and suggestions for future improvements, see the [ENHANCEMENTS.md](ENHANCEMENTS.md) file.

## Contact

You can reach Abdul via [LinkedIn](https://linkedin.com/in/abdul-zaid-0b39a3160) or email at **zaidabdul20@gmail.com** for collaboration or consulting opportunities.

## License

This project is licensed under the MIT License.  See the `LICENSE` file for more information.
