# Ontology for the Tourism Domain

This project focuses on the **creation, formalization, and implementation of an ontology** dedicated to the tourism sector. The ontology models key tourism-related concepts such as destinations, accommodations, activities, transportation, and reservations. It is developed using **Protégé** and structured using **OWL (Web Ontology Language)**.

📌 **Status:** 🚧 Work in progress – Some aspects need further refinement and validation.  
📄 **Full Report:** [OWS_Report.pdf](OWS_Report.pdf)  

## 📖 Overview  

- **Domain:** Tourism  
- **Tool:** [Protégé](https://protege.stanford.edu/) (Ontology Editor)  
- **Language:** OWL (Web Ontology Language)  
- **Purpose:** Structure and integrate knowledge in tourism to improve data organization, interoperability, and automated reasoning.  

## 🏗 Ontology Structure  

### 1️⃣ **Conceptualization**  
- **Key Entities:**  
  - **Destinations:** Cities, historical sites, natural attractions  
  - **Accommodations:** Hotels, apartments, rentals  
  - **Activities:** Guided tours, sports, cultural events  
  - **Transport:** Flights, buses, trains, car rentals  
  - **Reservations:** Booking systems for accommodations, transport, and activities  

- **Relationships Modeled:**  
  - Destinations contain tourist attractions  
  - Accommodations are located in destinations  
  - Activities are associated with destinations and tourists  
  - Reservations link tourists to services  

### 2️⃣ **Formalization & Implementation**  
- **Ontology Structure:**
  - **TBox (Terminology):** Defines concepts and their hierarchical relationships  
  - **ABox (Assertions):** Contains individuals and their attributes  

- **Defined Properties:**
  - **Object Properties:** Relationships between concepts (e.g., `located_in`, `offers_activity`)  
  - **Data Properties:** Attributes for entities (e.g., `name`, `price`, `capacity`)  

- **Consistency Testing:**  
  - Performed using **HermiT Reasoner** in Protégé  

### 3️⃣ **Interrogation with SPARQL**  
The ontology can be queried using **SPARQL** to extract relevant information, such as:  
- Listing all tourist attractions in a specific city  
- Retrieving all accommodations available in a destination  
- Finding all activities linked to a specific type of attraction  

## 📌 Project Status & Next Steps  

🚧 **This project is still under development.** Some areas require further work, including:  
- Refining ontology relationships and constraints  
- Expanding the dataset with more instances  
- Enhancing interoperability with external knowledge bases (e.g., DBpedia, Wikidata)  

## 📥 How to Use  

1. **Install Protégé:** Download from [Protégé Official Site](https://protege.stanford.edu/)  
2. **Load the OWL File:** Open the ontology file in Protégé  
3. **Explore & Modify:** Add new concepts, relations, and individuals as needed  
4. **Query with SPARQL:** Use Protégé's built-in query engine to retrieve information  

---

🛠 **Contributions & Feedback:**  
Any suggestions or contributions to improve this ontology are welcome! Feel free to review the model, provide feedback, or extend its capabilities.  

