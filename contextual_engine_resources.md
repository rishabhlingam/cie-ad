# Resources by Step — Contextual Intelligence Engine for Architectural Design

---

## Step 1 — Site Input & Design Prompt

### Tools

| Resource | Type | Link |
|---|---|---|
| **Mapbox GL JS** | Web mapping SDK for drawing site boundaries and polygon interaction | https://www.mapbox.com/mapbox-gljs |
| **Mapbox GL Draw** | Plugin for drawing polygons + calculating area in browser | https://docs.mapbox.com/mapbox-gl-js/example/mapbox-gl-draw/ |
| **Turf.js** | Open-source JavaScript spatial analysis library (area, centroid, buffer, intersect) | https://turfjs.org |
| **QGIS** | Open-source desktop GIS — upload/edit shapefiles, KML, GeoJSON boundaries | https://qgis.org |
| **GeoNode** | Open-source geospatial content management system with KML/GeoJSON support | https://geonode.org |

### Tutorials / Blogs

| Resource | Type | Link |
|---|---|---|
| **Custom Draw on Map using Mapbox + Turf.js** | Step-by-step tutorial (Medium) | https://medium.com/@anujsingh_wd/custom-draw-on-map-mapbox-gl-js-mapbox-draw-gl-turf-js-react-js-af579bdaa05f |
| **Analyze data with Turf.js and Mapbox GL JS** | Official Mapbox guide | https://docs.mapbox.com/help/tutorials/analysis-with-turf/ |
| **Open-Source Web-GIS Development Roadmap** | Comprehensive guide to GIS web stacks | https://www.geographyrealm.com/open-source-web-gis-development-roadmap/ |
| **Awesome Geospatial** | Curated list of all geospatial tools (GitHub) | https://github.com/sacridini/Awesome-Geospatial |

---

## Step 2 — Multi-Source Data Layer

### Data APIs & Sources

| Resource | Type | Link |
|---|---|---|
| **OpenFEMA API** | Free flood, disaster, and hazard data from FEMA | https://www.fema.gov/about/openfema/api |
| **FEMA National Flood Hazard Layer (NFHL)** | Geospatial flood zone database | https://www.fema.gov/flood-maps/national-flood-hazard-layer |
| **National Flood Data API (v3)** | FEMA flood zone API for embedding in applications | https://docs.nationalflooddata.com/dataservice/v3/index.html |
| **US Census API / ACS** | Demographics, land use, socioeconomic data by geography | https://www.census.gov/data/developers.html |
| **OpenStreetMap + Overpass API** | Street networks, building footprints, land use | https://overpass-turbo.eu |
| **Regrid Parcel API** | Parcel and land use data for US properties | https://regrid.com |

### Research Papers

| Resource | Type | Link |
|---|---|---|
| **Social Media Data in Urban Design and Landscape Research** | Comprehensive literature review (MDPI, 2022) — covers LBSM, NLP, image analysis | https://www.mdpi.com/2073-445X/11/10/1796 |
| **Understanding temporal and spatial patterns via geotagged social media** | ScienceDirect paper on using social data for urban activity analysis | https://www.sciencedirect.com/science/article/pii/S0198971522001788 |
| **Categorizing urban space based on visitor density and diversity** | Uses Twitter geotags to classify urban spaces (ResearchGate) | https://www.researchgate.net/publication/365624901 |
| **Extracting Patterns of Urban Activity from Foursquare** | Probabilistic model for urban activity using social check-ins (arXiv) | https://arxiv.org/pdf/1604.04649 |
| **Social media and the city — socio-spatial inequality** | Using geotagged tweets for urban analysis + planning (ScienceDirect) | https://www.sciencedirect.com/science/article/abs/pii/S0169204615000523 |

### Tools

| Resource | Type | Link |
|---|---|---|
| **rfema (R package)** | Clean API wrapper for OpenFEMA data | https://docs.ropensci.org/rfema/ |
| **PostGIS / PostgreSQL** | Spatial database for storing and querying heterogeneous geo data | https://postgis.net |
| **GeoServer** | Open-source server for sharing geospatial data via OGC standards | https://geoserver.org |

---

## Step 3 — Contextual Knowledge Engine & Digital Twin

### Research Papers

| Resource | Type | Link |
|---|---|---|
| **Knowledge graph-based data integration for digital twins of built assets** | Proposes KG-centered system using IFC + IoT ontologies (ScienceDirect, 2023) | https://www.sciencedirect.com/science/article/pii/S0926580523003692 |
| **Comprehensive digital twin for infrastructure: ontology and graph paradigm** | Novel DT modeling paradigm with 5-element ontology (ScienceDirect, 2024) | https://www.sciencedirect.com/science/article/abs/pii/S1474034624003951 |
| **Ontologies in digital twins: A systematic literature review** | Reviews 82 papers on semantic tech in digital twins | https://vdegeler.com/files/24ontology-dt.pdf |
| **A Survey on Knowledge Graph Applications in Smart Cities** | Reviews KG use cases in smart city platforms (ACM, 2024) | https://dl.acm.org/doi/10.1145/3672615 |
| **LSDTs: LLM-Augmented Semantic Digital Twins** | Combines LLMs with RDF semantic graphs for infrastructure planning (arXiv, 2025) | https://arxiv.org/html/2508.06799v1 |
| **Reference Architecture and Ontology Framework for Digital Twin Construction** | Proposes DiCon ontologies for construction knowledge integration | https://www.researchgate.net/publication/382056481 |

### Tools & Frameworks

| Resource | Type | Link |
|---|---|---|
| **Neo4j** | Industry-standard graph database for building knowledge graphs | https://neo4j.com |
| **GraphRAG (Neo4j + Microsoft)** | Combines knowledge graphs with LLM RAG for contextual retrieval | https://neo4j.com/blog/developer/graphrag-and-agentic-architecture-with-neoconverse/ |
| **Microsoft GraphRAG** | Open-source GraphRAG framework (mid-2024 release) | https://github.com/microsoft/graphrag |
| **GraphRAG + Qdrant + Neo4j** | Hybrid vector + graph retrieval architecture tutorial | https://qdrant.tech/documentation/examples/graphrag-qdrant-neo4j/ |
| **Protégé** | Free ontology editor for building OWL/RDF ontologies | https://protege.stanford.edu |
| **LangChain** | Framework for chaining LLM calls with structured data retrieval | https://www.langchain.com |

### Tutorials / Blogs

| Resource | Type | Link |
|---|---|---|
| **Setting Up GraphRAG with Neo4j** | Step-by-step implementation guide (Analytics Vidhya) | https://www.analyticsvidhya.com/blog/2024/11/graphrag-with-neo4j/ |
| **Semantic GraphRAG with Neo4j, Qdrant & OpenAI** | Full implementation walkthrough (Medium) | https://medium.com/@visrow/semantic-graphrag-implementation-guide |
| **Building Knowledge Graph RAG Systems on Databricks** | Enterprise-scale GraphRAG deployment guide | https://www.databricks.com/blog/building-improving-and-deploying-knowledge-graph-rag-systems-databricks |

---

## Step 4 — Concept Generation (AI + LLM)

### Research Papers

| Resource | Type | Link |
|---|---|---|
| **From tools to partners: LLMs transforming urban planning** | Comprehensive review of LLM applications in urban planning + design (ScienceDirect, 2025) | https://www.sciencedirect.com/science/article/pii/S2666651025000191 |
| **Generative AI in architectural design: Application, data, and evaluation methods** | Systematic review of 161 papers (2014–2024) on GenAI in architecture | https://www.sciencedirect.com/science/article/abs/pii/S0926580525002146 |
| **Generative AI for complex urban planning** | Reviews 183 publications tracing GenAI evolution (ScienceDirect, 2026) | https://www.sciencedirect.com/science/article/pii/S2226585625001888 |
| **Prompts for planning-AI integration** | LLM prompt design frameworks for urban planning (ScienceDirect, 2025) | https://www.sciencedirect.com/science/article/pii/S219985312500201X |
| **Architectural Design with LLMs — ETH Zurich** | Research on LLM-based agents for conceptual form-finding and layout generation | https://designplusplus.ethz.ch/research/ongoing-projects/interacting-with-architectural-generative-design-models-using-la.html |
| **Generative Transformers for Design Concept Generation** | Uses NLG (pre-trained language models) for early-stage design concept generation (arXiv) | https://arxiv.org/pdf/2211.03468 |
| **Agentic, Multimodal LLM for Conversational Architectural Design** | Explores conversational AI loops in architectural design processes (2025) | https://www.tandfonline.com/doi/full/10.1080/00038628.2025.2586655 |

### Tools

| Resource | Type | Link |
|---|---|---|
| **Claude API (Anthropic)** | Recommended LLM for structured context + concept generation | https://docs.anthropic.com |
| **OpenAI GPT-4 API** | Alternative LLM API with structured output + function calling | https://platform.openai.com |
| **LlamaIndex** | Framework for connecting LLMs to structured data sources and knowledge graphs | https://www.llamaindex.ai |

---

## Step 5 — Design Exploration Outputs (Massing + Metrics)

### Tools

| Resource | Type | Link |
|---|---|---|
| **Autodesk Forma (formerly Spacemaker)** | Cloud-based AI massing + site analysis — sun, wind, noise, embodied carbon in real time | https://www.autodesk.com/products/forma-site-design/overview |
| **Rhino 3D + Grasshopper** | Industry-standard parametric design + massing tool for architects | https://www.rhino3d.com / https://www.grasshopper3d.com |
| **TestFit** | Rapid building feasibility and massing generation tool | https://testfit.io |
| **Finch 3D** | AI-assisted floor plan and massing exploration | https://www.finch3d.com |
| **Hypar** | Cloud-based parametric building generation platform with custom function authoring | https://hypar.io |
| **Three.js / Babylon.js** | Web-based 3D massing visualization in browser | https://threejs.org |

### Research Papers

| Resource | Type | Link |
|---|---|---|
| **Sketch-to-Architecture: GenAI-aided Architectural Design** | Converts text prompts → floorplans → Rhino 3D massing via Grasshopper (arXiv, 2024) | https://arxiv.org/html/2403.20186 |
| **Parametric Design in Architecture: Algorithmic Form Generation** | Reviews Grasshopper + Rhino for algorithmic massing and form generation | https://americanjournal.org/index.php/ajper/article/view/3069 |
| **Algorithmic Urban Design in Grasshopper: Data-Driven Site Analysis & Massing** | Grasshopper workflow tutorial for site analysis and parametric massing | https://parametric-architecture.com/algorithmic-urban-design-in-grasshopper/ |

### Reviews / Blogs

| Resource | Type | Link |
|---|---|---|
| **Autodesk Forma Full Review 2026** | Detailed feature review of Forma Site Design (illustrarch) | https://illustrarch.com/articles/design-softwares/73363-autodesk-forma-review.html |
| **Best AI Tools for Architects 2026** | Comprehensive roundup including Forma, TestFit, Finch, Cove.tool | https://aibuildingtools.com/blog/best-ai-tools-for-architects |
| **Bridging AI and Parametric Design: Grasshopper MCP Server** | Connects LLMs directly to Grasshopper for AI-driven massing scripts | https://skywork.ai/skypage/en/ai-parametric-design-grasshopper/1981893662536208384 |

---

## Step 6 — Refine & Iterate + Export

### Tools

| Resource | Type | Link |
|---|---|---|
| **Speckle** | Open-source AEC data hub — connects Revit, Rhino, Grasshopper, IFC, GIS with versioning + real-time sync | https://speckle.systems |
| **ArchiLabs Studio Mode** | Conversational AI design interface with IFC export and BIM automation | https://archilabs.ai |
| **Autodesk Revit + AI Assistant** | BIM platform with conversational assistant for design refinement | https://www.autodesk.com/products/revit/overview |
| **Rhino.Inside.Revit** | Runs Rhino + Grasshopper inside Revit for seamless massing-to-BIM workflows | https://www.rhino3d.com/inside/revit/ |
| **IFC Exporter for Revit (open source)** | Autodesk's open-source IFC export pipeline for Revit models | https://github.com/Autodesk/revit-ifc |
| **QGIS** | Export to GIS-compatible formats (.shp, GeoJSON) for urban analysis | https://qgis.org |

### Research Papers

| Resource | Type | Link |
|---|---|---|
| **Conversational AI-enhanced framework for early-stage architectural exploration** | Proposes multi-perspective AI design partner with context awareness + iterative feedback (Springer, 2025) | https://link.springer.com/article/10.1007/s44223-025-00092-5 |
| **Agentic Multimodal LLM for Conversational Architectural Design** | Explores human-AI feedback loop in architecture with agentic capabilities (2025) | https://www.tandfonline.com/doi/full/10.1080/00038628.2025.2586655 |

### Tutorials / Blogs

| Resource | Type | Link |
|---|---|---|
| **Speckle: The Open-Source Cloud Data Platform** | In-depth feature review of Speckle Intelligence and BIM interoperability (AEC Magazine) | https://aecmag.com/features/speckle-the-open-source-cloud-data-platform/ |
| **How Rhino3D & Grasshopper Transform Architectural Design** | Covers Rhino.Inside integration with Revit and AI design tools | https://paacademy.com/blog/how-rhino3d-grasshopper-transform-architectural-design |
| **AI-Powered Revit Automation** | Guide to conversational BIM automation with IFC export | https://archilabs.ai/posts/ai-powered-revit-automation |
| **Revit 2027 AI & IFC Changes** | Latest Revit updates including MCP-based AI assistant + improved IFC export | https://architosh.com/2026/04/autodesk-revit-2027-big-new-ai-and-graphics-changes/ |

---

## Cross-Cutting Resources (Applicable to Multiple Steps)

| Resource | Type | Relevant Steps |
|---|---|---|
| **CityGML / OGC Standards** | Open standard for 3D city models (geometry + semantics) | 2, 3, 5 |
| **IFC (Industry Foundation Classes)** | Open BIM data standard for interoperability | 1, 5, 6 |
| **OSMnx (Python)** | Download and analyze OpenStreetMap street networks + buildings | 2, 3 |
| **GeoPandas** | Python library for spatial data manipulation | 2, 3 |
| **LangChain / LlamaIndex** | LLM orchestration frameworks for structured data pipelines | 3, 4, 6 |
| **Hugging Face (Sentence Transformers)** | Pre-trained embedding models for text vectorization | 3, 4 |
| **Hypar Elements** | Open-source .NET library for building element geometry | 5, 6 |

---

*Resources compiled May 2026. All links verified at time of research.*
