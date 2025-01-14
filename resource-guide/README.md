# 🌱 EcoHack for Restoration Ecology 🌿  
### Hackathon Application Ideas 💡  

1. **Intelligent Chatbots** 🤖  
   - Provide personalized recommendations  
   - Chat with an ecologist  
   - Chat with research papers  
   - Incorporate evidence  
   - Include information on the reliability of results  
   
2. **LLM-powered Search System for Ecologists**
   - Start from the [ORKG ASK](https://ask.orkg.org/) platform  
     - Integrate the device of follow-up questions to the first search question 
	 - Implement a chat with your paper feature
	 - Implement feedback mechanisms
	 - others ...

3. **Convert Research Papers into Presentation Slide Decks** 🖼️  

4. **Data Analysis and Visualization** 📊  
   - Summarize data findings  
     - Compute topic models and display  
     - Generate summaries in various styles: lay or scientific  
   - Create visualizations based on data trends  
   - Provide natural language explanations of complex datasets  

5. **Build a Knowledge Graph of Findings in Ecology** 🧠  
   - Identify information extraction targets  
     - Build comparisons using [ORKG](https://orkg.org/)  
   - Extract information about causal and mechanistic models  
   - Detect concept/term ambiguity (e.g., multiple meanings of "enemy")  

6. **Search Interfaces** 🔎  
   - Fair and diverse results  
     - Rank by preferences (e.g., temporal, location, discipline)  
     - Label source types (scientific papers, grey literature, etc.)  
   - Query builder with templates and SPARQL translation  

7. **Tools for Synthesizing Research Papers** 📚  
   - Detect ecosystems and map them  
     - Use [IUCN's ecosystem typology](https://iucn.org/resources/publication/iucn-global-ecosystem-typology-20)  
   - Extract models/variables  
   - Detect species and link them to ontologies (images?)  
   - Summarize papers for different audiences (e.g., laypeople via [BioLaySumm](https://biolaysumm.org/))  

8. **Incorporating Grey Literature** 🗂️  
   - Combine results from scientific and grey literature, retaining source information  

9. **Summarizing IPBES Reports** 🌏  
   - Explore [global biodiversity reports](https://www.ipbes.net/assessment-reports/ldr)  
   - Task ideas: topic modeling, chatbots, or Q&A over reports  

10. **Futzy 2.0** on [Github](https://github.com/EcoWeaver/Futzy) 🌐  
   - Support for fuzzy cognitive map (FCM) extensions (delay, conditional...)  
   - Merge two FCMs  

11. **Developing an Ontology with LLMs** 🧬  
    - Input: hypotheses, abstracts, and datasets  
    - Use LLMs for term extraction and ontology building  
    - Define hierarchies and relations, evaluate via [INBIO](https://bioportal.bioontology.org/ontologies/INBIO)  

---

### 🔗 Resources  
**Scientific Papers Corpus**  
Consider compiling a corpus of scientific papers for your project! Here are some starting points:  
- **Example Papers**  
  1. [Facets Journal Article (2022)](https://www.facetsjournal.com/doi/full/10.1139/facets-2022-0157)  
  2. [Ecological Restoration Research Review (2020)](https://journals.lww.com/coas/fulltext/2020/18030/a_review_of_ecological_restoration_research_in_the.9.aspx)  
- **Sources for Building Your Corpus**  
  - [Web of Science](https://www.webofscience.com/wos/)  
  - [Unpaywall](https://unpaywall.org/)  
  - [ASK.ORKG Semantic Neural Search API](https://api.ask.orkg.org/docs#tag/Semantic-Neural-Search)  

#### 🔗 Additional Resources  

Here’s a comprehensive list of tools, datasets, and platforms to fuel your hackathon creativity:  

- [Eco-Evidence Toolkit](https://toolkit.ewater.org.au/Tools/Eco-Evidence)  
- [Environmental Evidence CEEDER](https://environmentalevidence.org/ceeder-search/)  
- [Open Knowledge Maps](https://github.com/OpenKnowledgeMaps)  
- [Hi-Knowledge](https://hi-knowledge.org/)  
- [Conservation Evidence](https://www.conservationevidence.com/)  
- [EcoDIVER Overview](https://www.epa.gov/ecodiver/about-ecodiver)  
- [EcoDIVER Resources](https://www.epa.gov/ecodiver/ecodiver-resources)  
- [BioLaySumm](https://biolaysumm.org/) – A dataset of biomedical research articles with lay summaries  
- [BiodivNERE-Gold](https://zenodo.org/records/6575865) – Gold standard corpora for named entity recognition and relation extraction in biodiversity  
  - [Accompanying Paper](https://bdj.pensoft.net/article/89481/instance/7788834/)  

**Hypothesis Corpus**  
- [Taxonomy of Hypotheses](https://v2020.hi-knowledge.org/invasion-biology/)  
- Publications:  
  - [Abstract-Level Annotated Corpus](https://aclanthology.org/2022.wiesp-1.5/)  
  - [Span-Level Annotated Corpus](https://link.springer.com/chapter/10.1007/978-3-031-63536-6_2)  

**Ontologies**  
- [Invasion Biology Ontology (INBIO)](https://bioportal.bioontology.org/ontologies/INBIO) – Consider building something similar for restoration ecology  
- [BioPortal](https://bioportal.bioontology.org/)  
- [BioDiv Portal](https://biodivportal.gfbio.org/)  

**Other Inspiration**  
- [British Ecological Society – Applied Ecology Resources](https://www.britishecologicalsociety.org/applied-ecology-resources/) – Think about transferring ideas to restoration ecology  


#### 🔗 AI or LLM-related Resources  

- [**mem0**](https://github.com/mem0ai/mem0): Enhances AI assistants with an intelligent memory layer for personalized interactions, adapting to user needs and improving over time.  
- [**PaperScraper**](https://github.com/jannisborn/paperscraper): A Python package for scraping publication metadata and full PDFs from sources like PubMed, arXiv, and more, with tools for meta-analysis.  
- [**LangChain**](https://www.langchain.com/langchain): Quickly move from prototype to production using popular AI methods like RAG or chain-based approaches.  
- [**CrewAI**](https://www.crewai.com/): A platform for multi-agent automation, transforming complex tasks into seamless workflows.  
- [**Streamlit**](https://streamlit.io/): Create shareable web apps from Python scripts with no front-end experience required. Check out this [Q&A app](https://mastea-nhwpzz8fehvc9b3n5bhzya.streamlit.app/).  
- [**Marp**](https://marp.app/): Use Markdown to create beautiful slide decks effortlessly, focusing on storytelling and presentation.  
- [**Awesome Hackathon**](https://github.com/HappyHackingSpace/Awesome-Hackathon): A comprehensive list of resources to inspire and support your hackathon projects.  


With these resources, you’ll have a solid foundation for creating innovative solutions for the EcoHack! 🚀


---

### 🛠️ Hackathon Application Workflows  
1. **Search & Answer Workflow**  
   - Retrieve relevant documents to questions in restoration ecology  
   - Test systems, analyze results, and answer questions from top-ranked documents  

2. **Slide Deck Generation**  
   - Convert research papers into engaging presentation decks  
   - Tools: [MARP](https://marp.app/)  

3. **Information Extraction Workflow**  
   - Build ORKG comparisons of research contributions  
   - Tools: [PaperScraper](https://github.com/jannisborn/paperscraper), [LlamaIndex](https://www.llamaindex.ai/)  

---

### 💭 Brainstorming Inspiration  
Explore these tools and projects to spark ideas:  
- [Papeg.ai](https://papeg.ai/#)  
- [Restor.eco](https://restor.eco)  
- [Global Restore Project](https://globalrestoreproject.com/)  

---

### 🌟 **Final Tip** 🌟  
**Get creative and draw inspiration from other domains, but remember—the *coolest prizes* go to solutions that tackle challenges in restoration ecology head-on!** 🌿✨  

