# Awesome Azure - Advanced Analytics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Awesome big data and advanced analytics resources for the Microsoft Azure Cloud

1. Azure General
1. AI and Machine Learning
1. Cloud Scale Analytics

![Microsoft AI platform](img/CIS.png)

## Contributing

Your contributions are welcomed! Please send a pull request to contribute. Make sure you check out the the [Markdown Syntax](https://guides.github.com/features/mastering-markdown/)
guide and add the link you want to contribute at the bottom of the appropriate category.

We are in a transition to adopt the best practice from [this](https://github.com/sindresorhus/awesome/blob/master/pull_request_template.md) list guideline.

As part of this efforts, your contributions are appreciated on the items with `- DESCRIPTION NEEDED.`, or the ones without the descriptions; You can verfity the link and add description. Try to avoid marketing message but use helpful/objective summary of what it is. Please end the sentence with `.`(dot).

:heart: will be added to only carefully chosen items (ideally less than 2-3 per category for visibility) after review.

## Table of Contents

1. [Azure General](#azure-general)

    - [Getting to know Azure](#getting-to-know-azure)
    - [Training Resources](#training-resources)
    - [Technical Certifications](#technical-certifications)

1. [AI and Machine Learning](#microsoft-ai-platform)

    - Intelligent Apps and Agents
      - [Azure Cognitive Services](#azure-cognitive-services)
      - [Microsoft Bot Framework](#microsoft-bot-framework)

    - Knowledge Mining
      - [Azure Cognitive Search](#azure-cognitive-search)

    - Machine Learning
      - [Azure Machine Learning](#azure-machine-learning)
      - [Deep Learning on Azure](#deep-learning-on-azure)
      - [Jupyter Notebooks](#jupyter-notebooks)
      - [Microsoft Machine Learning Server](#microsoft-machine-learning-server)

1. [Cloud Scale Analytics](#cloud-scale-analytics)

    - [Azure Analysis Services](#azure-analysis-services)
    - [Azure Cosmos DB](#azure-cosmos-db)
    - [Azure Database for MariaDB](#azure-database-for-mariadb)
    - [Azure Database for MySQL](#azure-database-for-mysql)
    - [Azure Database for PostgreSQL](#azure-database-for-postgresql)
    - [Azure Databricks](#azure-databricks)
    - [Azure Data Catalog](#azure-data-catalog)
    - [Azure Data Explorer](#azure-data-explorer)
    - [Azure Data Factory](#azure-data-factory)
    - [Azure Data Lake](#azure-data-lake)
    - [Azure Event Hubs](#azure-event-hubs)
    - [Azure HDInsight](#azure-hdinsight)
    - [Azure IoT](#azure-iot)
    - [Azure Redis Cache](#azure-redis-cache)
    - [Azure SQL Database](#azure-sql-database)
    - [Azure SQL Data Warehouse](#azure-sql-data-warehouse)
    - [Azure Stream Analytics](#azure-stream-analytics)
    - [Azure Time Series Insights](#azure-time-series-insights)
    - [Microsoft Power BI](#microsoft-power-bi)

- - -

## Azure General

### Getting to know Azure

- [Free Azure Subscription](https://azure.microsoft.com/en-us/free/) - Guide on creating new free Azure subscription and get started on Azure.
- Understand Azure services
  - :heart: [Azure Online Documentation](https://docs.microsoft.com/en-us/azure/) - Official go-to-page for most recent product documentation with quickstarts, samples, and tutorials.
  - [Azure Periodic Table](http://www.concurrency.com/landing/azure-periodic-table) - One-page summary of Azure services
  - [Azure Marketplace](https://azuremarketplace.microsoft.com/en-us/marketplace/) Find and deploy cloud softwares available on Azure.
- Code, Samples, Templates
  - [Azure GitHub Repos](https://github.com/Azure) - APIs, SDKs and open source projects from Microsoft Azure.
  - [Azure Code Samples](https://azure.microsoft.com/en-us/documentation/samples/)
  - [Azure Quickstart Templates](https://azure.microsoft.com/en-us/documentation/templates/)
- Related Awesome lists
  - [Awesome Azure: Azure for Startups](https://github.com/Azure-for-Startups/Content) - Startups key Azure resources and code sample.
  - [Awesome Azure: Tools, Guides, Tutorials](https://github.com/wangyihaier/awesome-azure) - A curated list of awesome Microsoft Azure tools, guides, tutorials.
  - [Awesome Azure: IoT](https://github.com/Azure/iot) - A curated list of awesome Azure Internet of Things projects and resources.
- Blogs, Forums, Newsletters
  - [Azure Blog](https://azure.microsoft.com/en-us/blog/) - Official blog with announcements, updates, tips and more.
  - [Azure Forums](https://azure.microsoft.com/en-us/support/forums/) - Ask questions, get answers and connect with Microsoft engineers and Azure community experts.
  - [Blogs: Artificial Intelligence](https://azure.microsoft.com/en-us/blog/topics/artificial-intelligence/) - DESCRIPTION NEEDED.
  - [Blogs: AzureCAT Guidance](https://blogs.msdn.microsoft.com/azurecat/) - DESCRIPTION NEEDED.
  - [Blogs: Big Data](https://azure.microsoft.com/en-us/blog/topics/big-data/) - DESCRIPTION NEEDED.
  - [Blogs: Database](https://azure.microsoft.com/en-us/blog/topics/database/) - DESCRIPTION NEEDED.
  - [Blogs: Data Platform](https://blogs.msdn.microsoft.com/data-platform/) - DESCRIPTION NEEDED.
  - [Blogs: Data Science](https://azure.microsoft.com/en-us/blog/topics/datascience/) - DESCRIPTION NEEDED.
  - [Blogs: Data Warehouse](https://azure.microsoft.com/en-us/blog/topics/data-warehouse/) - DESCRIPTION NEEDED.
  - [Blogs: IoT](https://azure.microsoft.com/en-us/blog/topics/internet-of-things/) - DESCRIPTION NEEDED.
  - [Azure Updates](https://azure.microsoft.com/en-us/updates/) - Learn about important Azure product updates, roadmap, and announcements. Subscribe to notifications to stay informed (RSS supported).
  - [Azure Weekly Newsletter](http://azureweekly.info/) - Azure Weekly is a summary of the week's top news to help you build on the Microsoft Azure Platform. Powered by endjin.com.
- :heart: [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/) - Application Architecture Guide, Reference Architecture, Microsoft Cloud Adoption Framework for Azure.
  - [Machine Learning at Scale](https://docs.microsoft.com/en-us/azure/architecture/data-guide/big-data/machine-learning-at-scale) - DESCRIPTION NEEDED.
  - [Azure Data Architecture Guide](https://docs.microsoft.com/en-us/azure/architecture/data-guide/) - DESCRIPTION NEEDED.
  - [Azure IoT reference architecture](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/iot/) - DESCRIPTION NEEDED.
  - [DevOps Checklist](https://docs.microsoft.com/en-us/azure/architecture/checklist/dev-ops) - DESCRIPTION NEEDED.
  - [Azure Solution Architectures](https://azure.microsoft.com/en-us/solutions/architecture/) - DESCRIPTION NEEDED.
  - [Azure Example Scenarios](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/) - DESCRIPTION NEEDED.
- Other general Azure Guides
  - [Azure Database Migration Guide](https://datamigration.microsoft.com/) - DESCRIPTION NEEDED.
- (Not just Azure) [Microsoft Research Podcast](https://www.microsoft.com/en-us/research/blog/category/podcast/) - Microsoft Research ongoing Podcast series, touching variety topics on Machine Learning / Machine Teaching, autonomous systems, Quantom Computing, and much more.

<!-- * (Retired) [Azure Interactives: Products, Design Patterns, Security](http://azureinteractives.azurewebsites.net/) -->

### Training Resources

- :heart: [Microsoft Learn](https://docs.microsoft.com/learn) - Interactive learning experience with real environment hands-on along with step-by-step guide.
- :heart: [Microsoft AI School](https://aischool.microsoft.com/en-us/home) - Start page for AI focused learning experiences.
  - [AI Business School](https://aischool.microsoft.com/en-us/business/learning-paths) - Learnings of AI for Business leaders, developed with INSEAD.
  - [Conversational AI](https://aischool.microsoft.com/en-us/conversational/learning-paths) - Curation of learning materials for Conversational AI.
  - [AI Services](https://aischool.microsoft.com/en-us/services/learning-paths) - Curation of learning materials for AI services by Microsoft.
  - [Machine Learning](https://aischool.microsoft.com/en-us/machine-learning/learning-paths) - Curation of learning materials for Machine Learning platform and services by Microsoft.
  - [Autonomous Systems](https://aischool.microsoft.com/en-us/autonomous-systems/learning-paths) - Curation of learning materials on AirSim, Microsoft Autonomous Systems AI Toolchain (Machine Teaching).
  - [Responsible AI](https://aischool.microsoft.com/en-us/responsible-ai/learning-paths) - Application of AI for social impact, design guidelines for Ethical AI, technical libraries like Homographic Encryption etc.

- Others
  - [Microsoft AI Lab](https://www.ailab.microsoft.com/) - DESCRIPTION NEEDED.
  - [Azure Training Courses](https://azure.microsoft.com/en-us/training/) - DESCRIPTION NEEDED.
  - [Azure Certification: Where to Start?](https://buildazure.com/2016/09/29/azure-certification-where-to-start-2016-edition/) - DESCRIPTION NEEDED.
  - [Learn AI @ MS](http://learnanalytics.microsoft.com/home/index) - DESCRIPTION NEEDED.
  - [Learn Analytics Materials](https://azure.github.io/learnAnalytics-public/) - DESCRIPTION NEEDED.
  - [edX.org Courses on Azure](https://www.edx.org/course?search_query=azure) - DESCRIPTION NEEDED.
  - [Microsoft Hands-On Labs](https://www.microsoft.com/handsonlabs) - DESCRIPTION NEEDED.
  - [Microsoft Cloud Workshops](https://github.com/Microsoft/MCW) - DESCRIPTION NEEDED.
  - [Azure Readiness GitHub Repos](https://github.com/Azure-Readiness) - DESCRIPTION NEEDED.
  - [Academic Resources for Computer Science](https://github.com/Microsoft/computerscience) - DESCRIPTION NEEDED.
  - [Videos: Channel 9](https://channel9.msdn.com/) - DESCRIPTION NEEDED.
  - [AWS to Azure Services Comparison](https://docs.microsoft.com/en-us/azure/architecture/aws-professional/services) - DESCRIPTION NEEDED.

### Technical Certifications

- [Microsoft Certifications](https://docs.microsoft.com/en-us/learn/certifications/) - Role-based certifications for Developers, Administrators, Solution Architects, Data Engineers, Data Scientists, AI Engineers, DevOps Engineers, Security Engineers, and Functional Consultants.
- Certifications (Role based)
  - [Data Engineer](https://docs.microsoft.com/en-us/learn/certifications/roles/data-engineer) - Data Engineers design and implement the management, monitoring, security, and privacy of data using the full stack of data services.
  - [Data Scientist](https://docs.microsoft.com/en-us/learn/certifications/roles/data-scientist) - Data Scientists apply machine learning techniques to train, evaluate, and deploy models that solve business problems.
  - [AI Engineer](https://docs.microsoft.com/en-us/learn/certifications/roles/ai-engineer) - AI Engineers use Cognitive Services, Machine Learning, and Knowledge Mining to architect and implement Microsoft AI solutions.
  - [DevOps Engineer](https://docs.microsoft.com/en-us/learn/certifications/roles/devops-engineer) - DevOps Engineers combine people, process, and technologies to continuously deliver valuable products and services that meet end user needs and business objectives.

- Exams
  - Active
    - [AI-100](https://docs.microsoft.com/en-us/learn/certifications/exams/ai-100) - Designing and Implementing an Azure AI Solution.
    - [DP-100](https://docs.microsoft.com/en-us/learn/certifications/exams/dp-100) - Designing and Implementing a Data Science Solution on Azure.
    - [DP-200](https://docs.microsoft.com/en-us/learn/certifications/exams/dp-200) - Implementing an Azure Data Solution.
    - [DP-201](https://docs.microsoft.com/en-us/learn/certifications/exams/dp-201) - Designing an Azure Data Solution.
  - Old
    - [70-473](https://www.microsoft.com/en-us/learning/exam-70-473.aspx) - Designing and Implementing Cloud Data Platform Solutions.
    - [70-475](https://www.microsoft.com/en-us/learning/exam-70-475.aspx) - Designing and Implementing Big Data Analytics Solutions.
    - [70-773](https://www.microsoft.com/en-us/learning/exam-70-773.aspx) - Analyzing Big Data with Microsoft R.
    - [70-774](https://www.microsoft.com/en-us/learning/exam-70-774.aspx) - Perform Cloud Data Science with Azure Machine Learning.
    - [70-775](https://www.microsoft.com/en-us/learning/exam-70-775.aspx) - Perform Data Engineering on Microsoft Azure HDInsight.
    - [70-776](https://www.microsoft.com/en-us/learning/exam-70-776.aspx) - Perform Big Data Engineering on Microsoft Cloud Services.
    - [70-778](https://www.microsoft.com/en-us/learning/exam-70-778.aspx) - Analyzing and Visualizing Data with Microsoft Power BI.

- MPPs now retired
  - [Microsoft Professional Program – Artificial Intelligence](https://academy.microsoft.com/en-us/professional-program/tracks/artificial-intelligence/)
  - [Microsoft Professional Program – Big Data](https://academy.microsoft.com/en-us/professional-program/big-data/)
  - [Microsoft Professional Program – Data Science](https://academy.microsoft.com/en-us/professional-program/data-science/)
  - [Microsoft Professional Program – Internet of Things](https://academy.microsoft.com/en-us/professional-program/tracks/internet-of-things/)

- - -

## AI + Machine Learning

*Artificial intelligence productivity for every developer and every scenario*

- [Overview](https://azure.microsoft.com/en-us/overview/ai-platform/) - DESCRIPTION NEEDED.
- [Blog](https://blogs.technet.microsoft.com/machinelearning/) - DESCRIPTION NEEDED.
- [AI News](https://news.microsoft.com/ai/) - DESCRIPTION NEEDED.
- [AI Gallery](https://gallery.azure.ai/) - DESCRIPTION NEEDED.
- [Solution Architectures](https://azure.microsoft.com/en-us/solutions/architecture/) - DESCRIPTION NEEDED.
- [Solution Templates](https://gallery.azure.ai/solutions) - DESCRIPTION NEEDED.
- [Application Gallery](https://appsource.microsoft.com/en-us/marketplace/apps?category=artifical-intelligence) - DESCRIPTION NEEDED.
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=cortana%20intelligence) - DESCRIPTION NEEDED.

### AI Apps and Agents
*Deliver breakthrough experiences in your apps*

#### Azure Cognitive Services
*A collection of APIs to tap into vision, speech, language, knowledge, and search technologies*

- [Overview (List of APIs)](https://azure.microsoft.com/en-us/services/cognitive-services/) - A comprehensive family of AI services and cognitive APIs to help you build intelligent apps.
- [Blog](https://azure.microsoft.com/en-us/blog/topics/cognitive-services/) - Azure Cognitive Services Blog.
- [Documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/) - Learn how to build intelligent and supported algorithms into apps, websites, and bots to see, hear, speak, understand, and interpret your user needs.
- Decison
  - Anomaly Detector
  - Content Moderator
  - [Personalizer](https://docs.microsoft.com/en-us/azure/cognitive-services/personalizer/how-personalizer-works) - The Personalizer resource, your learning loop, uses machine learning to build the model that predicts the top action for your content.
    - [Samples](https://github.com/Azure-Samples/cognitive-services-personalizer-samples)
    - [Demo1](https://personalizationdemo.azurewebsites.net/)
    - [Demo2](https://personalizercontentdemo.azurewebsites.net/)
    - [Microsoft Recommender Git repo](https://github.com/microsoft/recommenders) - Best Practices on Recommendation Systems.
- Language
  - Immersive Reader
  - Language Understanding
  - QnA Maker
  - Text Analytics
  - Translator Text
    - [Custom Translator Portal](https://portal.customtranslator.azure.ai/) - Learn how to customize Microsoft Translator's neural text and speech translation systems using your own training data to fit your style and terminology.
    - [Microsoft Translator](https://translator.microsoft.com/) - Translated conversations across devices, for one-on-one chats and for larger group interactions.
    - [Microsoft Translator Git Repo](https://github.com/MicrosoftTranslator) - Samples and utilities for Microsoft Translator.
- Speech
  - Speech to Text
  - Text to Speech
  - Speech Translation
  - Speaker Recognition
  - [Speech Studio](https://speech.microsoft.com/portal/)
    - [Custom Speech](https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/how-to-custom-speech) - A set of online tools that allow you to evaluate and improve Microsoft's speech-to-text accuracy for your applications, tools, and products.
    - [Custom Keyword](https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/speech-devices-sdk-create-kws) - Customizing your keyword is an effective way to differentiate your device and strengthen your branding.
    - Custom Voice - Record and upload training data to create a one-of-a-kind voice for your applications.
    - [Audio Content Creation](https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/how-to-audio-content-creation) - Manage SSML files.
    - Custom Commands - Easily configure commands, so that users can complete tasks using their voice.
    - [Speech CLI](https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/spx-basics?tabs=windowsinstall) - Command line tool for using the Speech service without writing any code, it is production-ready and can be scaled up to run larger processes using automated .bat or shell scripts.
- Vision
  - Computer Vision
  - Custom Vision
    - [Custom Vision Service Portal](https://www.customvision.ai/) - Customize your own state-of-the-art computer vision models that fit with your unique use case by just bringing a few examples of labeled images.
  - Face
  - Form Recognizer
  - Ink Recognizer
  - Video Indexer
    - [Video Indexer Portal](https://vi.microsoft.com/en-us/) - Easily extract insights from your videos and quickly enrich your applications to enhance discovery and engagement.
- Web search
  - Bing Autosuggest
  - Bing Custom Search
  - Bing Entity Search
  - Bing Image Search
  - Bing News Search
  - Bing Spell Check
  - Bing Video Search
  - Bing Visual Search
  - Bing Web Search
- [Cognitive Research Technologies](https://www.microsoft.com/en-us/research/group/cognitive-research/) - This set of innovative APIs and SDKs provides researchers and developers with an early look at emerging cognitive capabilities.
- From Ignite
  - :heart: [AIML20: Using Pre-Built AI to Solve Business Challenges](https://github.com/microsoft/ignite-learning-paths-training-aiml/tree/master/aiml20) - Computer Vision, Custom Vision, ONNX, and Personalizer.
- [Vowpal Wabbit](https://vowpalwabbit.org/) - Vowpal Wabbit for reinforcement learning (contextual bandit, learning to search), supervised learning (active learning, extreme
- [Recommendations Solution](https://gallery.cortanaintelligence.com/Tutorial/Recommendations-Solution) - (Old) Azure AI Gallery template for Recommendations Solution.
- Intelligent Kiosk
  - [GitHub](https://github.com/Microsoft/Cognitive-Samples-IntelligentKiosk) - Find several demos showcasing workflows and experiences built on top of the Microsoft Cognitive Services.
  - [MS Store](https://www.microsoft.com/en-sg/store/p/intelligent-kiosk/9nblggh5qd84) - On Microsoft Store: From face identification, emotion understanding and computer vision, to bots, text analytics and Bing services, the kiosk is your toolbox of AI demos, ready whenever you need an intuitive and engaging way of showing off Microsoft AI.
- [Tutorial: Build Mobile App with Chat](https://github.com/Microsoft/Build-Mobile-App-with-Chat) - The tutorial uses several Azure services to power a real-time chat infrastructure that is readymade for analytics.
- [Microsoft Azure Developer: Creating and Integrating AI with Azure Services](https://www.pluralsight.com/courses/microsoft-azure-developer-creating-integrating-ai-azure-services) - Explore the landscape of AI in the Microsoft space, and examine some practical examples to get you started.
- [Python SDK Samples](https://github.com/Azure-Samples/cognitive-services-python-sdk-samples) - Learn how to use the Cognitive Services Python SDK with these samples.
- [C# SDK Samples](https://github.com/Azure-Samples/cognitive-services-dotnet-sdk-samples) - Learn how to use the Cognitive Services C# SDK with these samples.
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=Cognitive%20Services) - Channel 9: Cognitive Services.

#### Microsoft Bot Framework
*A framework to build and deploy high-quality bots for conversation experiences*

- Get Started online documentations
  - [Azure Bot Service Overview](https://azure.microsoft.com/en-us/services/bot-service/) - DESCRIPTION NEEDED.
  - [Bot Framework Documentation](https://docs.microsoft.com/en-us/bot-framework/) - DESCRIPTION NEEDED.
  - [Azure Bot Service Documentation](https://docs.microsoft.com/en-us/bot-framework/azure/azure-bot-service-overview) - DESCRIPTION NEEDED.
- Highlights from official online documentations
  - [Bot Framework Overview](https://dev.botframework.com/) - DESCRIPTION NEEDED.
  - [Frequently Asked Questions](https://docs.microsoft.com/en-us/bot-framework/resources-bot-framework-faq) - DESCRIPTION NEEDED.
  - [Add Intelligence with Cognitive Services](https://docs.microsoft.com/en-us/bot-framework/cognitive-services-bot-intelligence-overview) - DESCRIPTION NEEDED.
  - [Bot Framework Emulator](https://docs.microsoft.com/en-us/bot-framework/debug-bots-emulator) - DESCRIPTION NEEDED.
  - [Bot Analytics](https://docs.microsoft.com/en-us/bot-framework/portal-analytics-overview) - DESCRIPTION NEEDED.
  - [Channel Inspector](https://docs.botframework.com/en-us/channel-inspector/channels/Skype/) - DESCRIPTION NEEDED.
  - [Principles of Bot Design](https://docs.microsoft.com/en-us/bot-framework/bot-design-principles) - DESCRIPTION NEEDED.
  - [Templates in the Azure Bot Service](https://docs.microsoft.com/en-us/bot-framework/azure-bot-service-templates) - DESCRIPTION NEEDED.
- Blogs
  - [Blog](https://blog.botframework.com/) - DESCRIPTION NEEDED.
  - [Great List of Resources](https://blogs.msdn.microsoft.com/smich/2016/09/30/microsoft-bot-framework-resources/) - DESCRIPTION NEEDED.
- Related GitHub repos
  - [Bot Framework WebChat](https://github.com/microsoft/botframework-webchat) - DESCRIPTION NEEDED.
  - [Bot Builder SDK](https://github.com/Microsoft/BotBuilder) - DESCRIPTION NEEDED.
  - [Bot Builder Samples](https://github.com/Microsoft/BotBuilder-Samples) - DESCRIPTION NEEDED.
- Relevant services
  - [Language Understanding Intelligent Service](https://www.luis.ai/) - DESCRIPTION NEEDED.
  - [QnA Maker](https://qnamaker.ai/) - DESCRIPTION NEEDED.
- Training materials
  - [Video: Getting Started with Bots](https://mva.microsoft.com/en-us/training-courses/getting-started-with-bots-16759?l=2zTAb2HyC_3504668937) - DESCRIPTION NEEDED.
  - [Channel 9 Videos](https://channel9.msdn.com/Search?term=bot%20framework) - DESCRIPTION NEEDED.
- e-books
  - [Developing Bots with Microsoft Bots Framework: Create Intelligent Bots using MS Bot Framework and Azure Cognitive Services](https://read.amazon.com/kp/embed?asin=B077Z79PW2&preview=newtab&linkCode=kpe&ref_=cm_sw_r_kb_dp_-rYfFbJ39A62W) - by Srikanth Machiraju, Ritesh Modi

### Knowledge Mining
*Uncover latent insights from all your content*

#### Azure Cognitive Search
*AI-powered cloud search service for web and mobile app development*

- Official Getting Started documentations
  - [Overview](https://azure.microsoft.com/en-us/services/search/) - DESCRIPTION NEEDED.
  - [Blog](https://azure.microsoft.com/en-us/blog/tag/azure-search/) - DESCRIPTION NEEDED.
  - [Documentation](https://docs.microsoft.com/en-us/azure/search/) - DESCRIPTION NEEDED.
  - [Cognitive Search](https://docs.microsoft.com/en-us/azure/search/cognitive-search-concept-intro)
- Demos - DESCRIPTION NEEDED.
  - [The MET](http://art-explorer.azurewebsites.net/) - DESCRIPTION NEEDED.
  - [JFK files](https://jfk-demo.azurewebsites.net/) - DESCRIPTION NEEDED.
  - [Wolter Kluwer](https://wolterskluwereap.azurewebsites.net/) - DESCRIPTION NEEDED.
  - [Document Search (healthcare/news/legal/HR)](http://documentsearch.azurewebsites.net/) - DESCRIPTION NEEDED.
  - [Contoso Manufacturing](https://contoso-manufacturing.azurewebsites.net/home) - DESCRIPTION NEEDED.
- Further industrial applications
  - Academic Dataset Integration
    - [Patent Search](https://docs.microsoft.com/en-us/academic-services/graph/tutorial-azure-search-org-patents)  - DESCRIPTION NEEDED.
    - [Academic Reference Parsing](https://docs.microsoft.com/en-us/academic-services/graph/tutorial-azure-search-reference-parsing) - DESCRIPTION NEEDED.
- Bootcamps / Workshop Materials
  - [Knowledge Mining Bootcamp](https://github.com/Azure/LearnAI-KnowledgeMiningBootcamp) - Training material from Azure AI Customer Engineering (ACE) team.
  - [Knowledge Mining Solution Accelerator](https://github.com/Azure-Samples/azure-search-knowledge-mining) - Working sample with customizable UI template, custom skills, Power BI integration.
  - [Knowledge Mining Solution Accelerator (workshop)](https://github.com/Azure-Samples/azure-search-knowledge-mining/tree/master/workshops) - Step-by-step hands-on workshop guides from KM Solution Accelerator. 
  - :heart: [Mark Heffner's KM Workshop](https://github.com/MarkHeff/KM-Workshop-1) - In-depth workshop content including Knowledge Store, using web frontend, custom skills and Functions, Object Model, Analyzer and Scoring Profiles, Power BI etc.
  - From Ignite
    - :heart: [AIML10: Making Sense of your Unstructured Data with AI](https://github.com/microsoft/ignite-learning-paths-training-aiml/tree/master/aiml10) - Cover ingest-enrich-explore pattern, skillsets, cognitive skills, natural language processing, computer vision, and beyond.
- KM Solutions
  - [Sharepoint Connector](https://github.com/anevjes/AzureSearch.SharePointOnline) - DESCRIPTION NEEDED.
- Training materials
  - [Channel 9 Videos](https://channel9.msdn.com/Search?term=azure%20search&lang-en=true) - DESCRIPTION NEEDED.

### Machine Learning
*Quickly and easily build, train, deploy and manage your models*

#### Azure Machine Learning
*Cloud-based environment you can use to train, deploy, automate, manage, and track ML models.*

- Official Getting Started
  - [Overview](https://azure.microsoft.com/en-us/services/machine-learning/) - Overview of Azure ML.
  - [Documentation](https://docs.microsoft.com/en-us/azure/machine-learning/service/) - Go-to-page for the most recent documentation.
  - [What is Azure Machine Learning?](https://docs.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-ml) - Key concepts of Azure ML.
  - [Comparison of Microsoft ML Products](https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/data-science-and-machine-learning) - Inclusive of Cloud and On-premises solutions.
- Highlights from online documentations
  - [Architecture and Concepts](https://docs.microsoft.com/en-us/azure/machine-learning/concept-azure-machine-learning-architecture) - Workflow, Tools, Glossary.
  - :heart: [MLOps Concepts](https://docs.microsoft.com/en-us/azure/machine-learning/concept-model-management-and-deployment) - MLOps: Model management, deployment and monitoring with Azure Machine Learning.
  - e-book: [Agile Project Management with Azure DevOps: Concepts, Templates, and Metrics](https://read.amazon.com/kp/embed?asin=B07R6GJM2W&preview=newtab&linkCode=kpe&ref_=cm_sw_r_kb_dp_noYfFb42VBG7Y) - by Joachim Rossberg.
  - TwiML Podcast: [TwiML-Enterprise Readiness, MLOps and Lifecyle Management](https://twimlai.com/twiml-talk-321-enterprise-readiness-mlops-and-lifecycle-management-with-jordan-edwards/) - TwiML Podcast with Jordan Edwards.
  - [Automated Machine Learning](https://docs.microsoft.com/en-us/azure/machine-learning/concept-automated-ml) - Covers when to use it, how it works, pre-processing, how to avoid overfitting, ensemble models, imbalanced data etc.
  - [Interpretability](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-machine-learning-interpretability) - Why it matters, how it is implemented in Azure ML (SHAP, Mimic, Permutation Feature Importance, LIME, HAN, Tabular).
  - [Designer](https://docs.microsoft.com/en-us/azure/machine-learning/concept-designer) - No-code ML experience that spans data preparation, model training, and deployment.
  - [Enterprise Security](https://docs.microsoft.com/en-us/azure/machine-learning/concept-enterprise-security) - Authentication, authorization, network security, data encryption, monitoring, data flow diagrams with Azure ML.
- Samples, Tutorials, Reference Architectures, Templates, Solution Accelerators
  - :heart: [Azure ML Sample Notebooks](https://github.com/Azure/MachineLearningNotebooks) - The most recent code samples and tutorials of Azure ML.
  - :heart: [Examples: MLOps with Azure ML](https://github.com/microsoft/MLOps) - MLOps best practices and samples.
  - [Azure Architecture Center-AI and ML](https://docs.microsoft.com/en-us/azure/architecture/data-guide/big-data/machine-learning-at-scale) - ML at Scale Reference Architectures
    - [Training Python models](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/ai/training-python-models)
    - [Distributed training of deep learning models on Azure](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/ai/training-deep-learning)
    - [Batch scoring of Python machine learning models on Azure](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/ai/batch-scoring-python)
      - [Batch scoring of deep learning models on Azure](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/ai/batch-scoring-deep-learning)
      - [Real-time scoring of Python scikit-learn and deep learning models on Azure](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/ai/realtime-scoring-python)
      - [Machine learning operationalization (MLOps) for Python models using Azure Machine Learning](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/ai/mlops-python)
  - [Azure ML Workspace creation template (ARM)](https://github.com/Azure/azure-quickstart-templates/tree/master/201-machine-learning-advanced) - Advanced Azure Machine Learning workspace creation templates supporting approval(auto/manual) private endpoint, customer managed key, link to Azure Databricks workspace, virtual network.
  - [Solution Accelerator for Many Models](https://github.com/microsoft/solution-accelerator-many-models/) - Quick starter for Many Models with Azure ML using ParallelRunStep, Pipeline, Automated ML.
- SDK/CLI References
  - [Azure ML Python SDK](https://docs.microsoft.com/en-us/python/api/overview/azure/ml/intro)
  - [Azure ML R SDK](https://azure.github.io/azureml-sdk-for-r/reference/index.html)
  - [Azure ML CLI](https://docs.microsoft.com/en-us/azure/machine-learning/service/reference-azure-machine-learning-cli)
  - [Azure ML REST API](https://docs.microsoft.com/en-us/rest/api/azureml/)
- Blogs
  - [The AI Blog](https://blogs.microsoft.com/ai/) - From The Official Microsoft Blog.
- Learning materials
  - [Free eBook: Packt: Principles of Data Science, 5/10/2019](https://azure.microsoft.com/en-us/resources/principles-of-data-science/) - A beginner's guide to statistical techniques and theory.
  - [Video Series: Data Science for Beginners](https://azure.microsoft.com/en-us/documentation/articles/machine-learning-data-science-for-beginners-the-5-questions-data-science-answers/)
  - [Channel 9 Videos](https://channel9.msdn.com/Search?term=Azure%20Machine%20Learning)
- AI at Edge
  - [Vision AI DevKit docs](https://azure.github.io/Vision-AI-DevKit-Pages/docs/Get_Started/) - Get Started resources for VAIDK.
  - [Vision AI DevKit GitHub](https://github.com/Microsoft/vision-ai-developer-kit) - Vision AI Developer Kit Camera SDK, Machine Learning Notebooks, REST API PostMan collection, and other samples. 
  - [AI Video Intelligence Solution Accelerator](https://github.com/Azure-Samples/AI-Video-Intelligence-Solution-Accelerator) - How to deploy an end-to-end IoT Edge, including Azure Data Box Edge, based solution that processes camera feeds using CPU, GPU, and FPGA Azure Machine Learning accelerated models.
  - [NVIDIA Deepstream + Azure IoT Edge on a NVIDIA Jetson Nano](https://github.com/Azure-Samples/NVIDIA-Deepstream-Azure-IoT-Edge-on-a-NVIDIA-Jetson-Nano) - How to do real-time video analytics with NVIDIA DeepStream connected to Azure via Azure IoT Edge. It uses a NVIDIA Jetson Nano device that can process up to 8 real-time video streams concurrently.
- Non-Azure general and useful resources
  - [Data Science Lifecycle Process](https://github.com/dslp/dslp) - Best practices for data science teams, including issue templates, branching strategy, workflows, labels, standard repo structure.
- Azure ML Studio (classic)
  > Note: Check out the [Designer](https://docs.microsoft.com/en-us/azure/machine-learning/service/concept-designer) which is an evolution of Azure ML Studio (classic) and is now integrated with Azure Machine Learning.
  - [Overview](https://azure.microsoft.com/en-us/services/machine-learning-studio/)
  - [Documentation](https://docs.microsoft.com/en-us/azure/machine-learning/studio/)
  - [How to Choose Algorithms for AzureML Studio](https://azure.microsoft.com/en-us/documentation/articles/machine-learning-algorithm-choice/)
  - [Re-train a Machine Learning Model](https://azure.microsoft.com/en-us/documentation/articles/machine-learning-retrain-machine-learning-model/)
  - [Experiments Gallery](https://gallery.cortanaintelligence.com/experiments)
  - [Templates Gallery](https://gallery.cortanaintelligence.com/Collection/Machine-Learning-Templates-with-Azure-ML-Studio-1)
  - [R Client](https://github.com/RevolutionAnalytics/AzureML)
  - [Python Client](https://github.com/Azure/Azure-MachineLearning-ClientLibrary-Python)
  - [PowerShell Commandlet Library](https://github.com/hning86/azuremlps)
  - [Operationalizing ML Models](https://docs.microsoft.com/en-us/azure/machine-learning/studio/publish-a-machine-learning-web-service)
  - [Hands-On Lab](https://github.com/Azure-Readiness/hol-azure-machine-learning)
  - [Free eBook](https://blogs.msdn.microsoft.com/microsoft_press/2015/04/15/free-ebook-microsoft-azure-essentials-azure-machine-learning/)

#### Deep Learning on Azure
> This whole section is planned to be reorganized (product-related, tools, DL frameworks, MLOps/DevOps)

- Azure Data Science VMs
    > Azure VM images pre-installed and configured with popular tools for analytics and machine learning
  - [Overview](https://azure.microsoft.com/en-us/services/virtual-machines/data-science-virtual-machines/)
  - [Documentation](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/)
  - [What's included in the Data Science VM?](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/overview#whats-included-in-the-data-science-vm)
  - [Tools, Platforms, Utilities, and Samples](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/dsvm-tools-overview)
  - [Provision the Windows Data Science Virtual Machine](https://azure.microsoft.com/en-us/documentation/articles/machine-learning-data-science-provision-vm/)
  - [Provision the Linux Data Science Virtual Machine](https://azure.microsoft.com/en-us/documentation/articles/machine-learning-data-science-linux-dsvm-intro/)
  - [Provision the Deep Learning Virtual Machine](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/provision-deep-learning-dsvm)
  - [Ten things you can do on the Data science Virtual Machine](https://azure.microsoft.com/en-us/documentation/articles/machine-learning-data-science-vm-do-ten-things/)
  - [AzureSMR R Package: Manage and Interact with Azure Resources](https://github.com/Microsoft/AzureSMR)
  - [AzureDSVM R Package: Manage and Interact with DSVMs on Azure](https://github.com/Azure/AzureDSVM)
  - [AZKT: Azure Distributed Data Engineering Toolkit](https://github.com/Azure/aztk)
- Azure Batch AI
    > (TBU) Batch AI is now Azure ML Compute.
  - [Overview](https://azure.microsoft.com/en-us/services/batch-ai/)
  - [Documentation](https://docs.microsoft.com/en-us/azure/batch-ai/)
  - [Distributed Training Using Horovod](https://docs.microsoft.com/en-us/azure/batch-ai/tutorial-horovod-tensorflow)
  - [Recipes for AI Frameworks](https://github.com/Azure/BatchAI)
- Azure Machine Learning Service
  - [Overview](https://docs.microsoft.com/en-us/azure/machine-learning/service/)
  - [Train PyTorch models](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-train-pytorch)
  - [Train TensorFlow models](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-train-tensorflow)
  - [Tune Hyperparameters](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-tune-hyperparameters)
  - [Open Neural Network Exchange (ONNX)](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-build-deploy-onnx)
    - [ONNX](https://github.com/onnx)
    - [ONNX Runtime](https://github.com/microsoft/onnxruntime)
- Deep Learning on Azure Databricks
  - [Overview](https://docs.microsoft.com/en-us/azure/databricks/applications/deep-learning/)
  - [Deep Learning Pipelines](https://docs.microsoft.com/en-us/azure/databricks/applications/deep-learning/single-node-training/deep-learning-pipelines)
  - [Distributed Deep Learning](https://docs.microsoft.com/en-us/azure/databricks/applications/deep-learning/distributed-training/horovod-runner)
- Deep Learning on Azure HDInsight
  - [Microsoft Machine Learning for Apache Spark](https://github.com/Azure/mmlspark)
  - [Using CNTK and TensorFlow](https://blogs.technet.microsoft.com/machinelearning/2017/04/12/embarrassingly-parallel-image-classification-using-cognitive-toolkit-tensorflow-on-azure-hdinsight-spark/)
  - [Using Caffe](https://docs.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-deep-learning-caffe)
  - [Using BigDL](https://azure.microsoft.com/en-us/blog/use-bigdl-on-hdinsight-spark-for-distributed-deep-learning/)
  - [Using H2O.ai](https://azure.microsoft.com/en-us/blog/introducing-h2o-ai-with-on-azure-hdinsight-to-bring-the-most-robust-ai-platform-for-enterprises/)
- [Deep Learning Virtual Machine](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/deep-learning-dsvm-overview)
- [Operationalize Python, Spark, CNTK & TensorFlow Models on AzureML](https://docs.microsoft.com/en-us/azure/machine-learning/preview/deployment-setup-configuration)
- [Lab: Train & Serve TensorFlow Models with Kubernetes, Kubeflow and AKS](https://github.com/Azure/kubeflow-labs)
- [Developing and Operationalizing H2O.ai Models with Azure](https://blogs.technet.microsoft.com/machinelearning/2017/11/28/developing-and-operationalizing-h2o-ai-models-with-azure/)
- [Distributed Machine Learning Toolkit](http://www.dmtk.io/)
- [Microsoft ML Server - MicrosoftML Package](https://docs.microsoft.com/en-us/machine-learning-server/r/concept-what-is-the-microsoftml-package)
- [Visual Studio Tools for AI](https://www.visualstudio.com/downloads/ai-tools-vs/)
- Microsoft Cognitive Toolkit (CNTK)
  - [Overview](https://www.microsoft.com/en-us/cognitive-toolkit/)
  - [Blog](https://www.microsoft.com/en-us/cognitive-toolkit/blog/)
  - [Documentation](https://docs.microsoft.com/en-us/cognitive-toolkit/)
  - [Model Gallery](https://www.microsoft.com/en-us/cognitive-toolkit/features/model-gallery/)
  - [Python API](https://www.cntk.ai/pythondocs/index.html)
  - [Course Learning Materials](https://azure.github.io/learnAnalytics-DeepLearning-Azure/)
  - [Learning Plan - AI Applications](https://learnanalytics.microsoft.com/learningpaths/developing-advanced-ai-applications)
  - [Train & Serve Models with Kubernetes](https://blogs.technet.microsoft.com/machinelearning/2017/09/06/how-to-use-cognitive-toolkit-cntk-with-kubernetes-on-azure/)
  - [edX Course: Deep Learning Explained](https://www.edx.org/course/deep-learning-explained-microsoft-dat236x-0)
- e-books:
  - [Deep Learning with Azure: Building and Deploying Artificial Intelligence Solutions on the Microsoft AI Platform](https://read.amazon.com/kp/embed?asin=B07FP8P5R8&preview=newtab&linkCode=kpe&ref_=cm_sw_r_kb_dp_DpYfFbZ97Q8ZD) - by Mathew Salvaris, Danielle Dean, Wee Hyong Tok
- [Recommenders](https://github.com/microsoft/recommenders)

#### Jupyter Notebooks
*A web application to create documents containing live code, visualizations and explanatory text*

- [Standalone Notebooks](https://notebooks.azure.com/)
- [Azure ML Studio Notebooks](https://gallery.azure.ai/notebooks)
- [Azure HDInsight Spark Notebooks](https://docs.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-jupyter-notebook-kernels)
- Azure Notebooks
- Azure Machine Learning Notebook VMs

#### Microsoft Machine Learning Server
*A scalable and deployable enterprise-grade R and Python analytics platform*

- [Overview](https://www.microsoft.com/en-us/sql-server/machinelearningserver)
- [Documentation](https://docs.microsoft.com/en-us/machine-learning-server/index)
- [ML Server Blog](https://blogs.msdn.microsoft.com/mlserver/)
- [Tiger Team Blog](https://blogs.msdn.microsoft.com/microsoftrservertigerteam/)
- [Revolution Analytics Blog](http://blog.revolutionanalytics.com/)
- Python
  - [Client](https://docs.microsoft.com/en-us/machine-learning-server/install/python-libraries-interpreter)
  - [Function Library](https://docs.microsoft.com/en-us/machine-learning-server/python-reference/introducing-python-package-reference)
  - [Tutorials](https://docs.microsoft.com/en-us/machine-learning-server/python/tutorial-revoscalepy-pyspark)
  - [Samples](https://docs.microsoft.com/en-us/machine-learning-server/python/python-samples)
  - [Deploy and Manage Web Services](https://docs.microsoft.com/en-us/machine-learning-server/operationalize/python/how-to-deploy-manage-web-services)
  - [SQL Server Python Tutorials](https://docs.microsoft.com/en-us/sql/advanced-analytics/tutorials/sql-server-python-tutorials)
  - [Tools for Visual Studio](https://docs.microsoft.com/en-us/visualstudio/python/python-in-visual-studio)
- R
  - [Client](https://docs.microsoft.com/en-us/machine-learning-server/r-client/what-is-microsoft-r-client)
  - [Function Library](https://docs.microsoft.com/en-us/machine-learning-server/r-reference/introducing-r-server-r-package-reference)
  - [Tutorials](https://docs.microsoft.com/en-us/machine-learning-server/r/tutorial-introduction)
  - [Samples](https://docs.microsoft.com/en-us/machine-learning-server/r/r-samples)
  - [Deploy and Manage Web Services](https://docs.microsoft.com/en-us/machine-learning-server/operationalize/how-to-deploy-web-service-publish-manage-in-r)
  - [SQL Server R tutorials](https://docs.microsoft.com/en-us/sql/advanced-analytics/tutorials/sql-server-r-tutorials)
  - [Tools for Visual Studio](https://docs.microsoft.com/en-us/visualstudio/rtvs/)
- SQL Server ML Services
  - [Overview](https://docs.microsoft.com/en-us/sql/advanced-analytics/getting-started-with-machine-learning-services)
  - [Tutorials](https://docs.microsoft.com/en-us/sql/advanced-analytics/tutorials/machine-learning-services-tutorials)
  - [R Samples & Templates](https://github.com/Microsoft/SQL-Server-R-Services-Samples)
  - [Model Management](https://blogs.technet.microsoft.com/dataplatforminsider/2016/10/17/sql-server-as-a-machine-learning-model-management-system/)
  - [eBook: Data Science with SQL Server](https://blogs.technet.microsoft.com/machinelearning/2016/10/19/data-science-with-microsoft-sql-server-2016-free-ebook/)
- [Compute Contexts](https://docs.microsoft.com/en-us/machine-learning-server/r/concept-what-is-compute-context)
- [Operationalization of Models](https://docs.microsoft.com/en-us/machine-learning-server/operationalize/concept-operationalize-deploy-consume)
- [Configuring ML Server to Operationalize Analytics on Azure](https://blogs.msdn.microsoft.com/mlserver/2017/11/21/configuring-microsoft-machine-learning-server-to-operationalize-analytics-using-arm-templates/)
- [Microsoft R Application Network](https://mran.microsoft.com/)
- [Revolution Analytics GitHub Repos](https://github.com/RevolutionAnalytics)
- [Sample Code and Data for R Server and R Client](https://github.com/Microsoft/microsoft-r)
- [A Collection of Simple R Demos](https://github.com/bensadeghi/R-demos/tree/master/MS-R)
- [eBook: Introduction to Microsoft R](https://smott.gitbooks.io/introduction-to-microsoft-r-server/content/)
- [Video Series: Introduction to Microsoft R](https://channel9.msdn.com/Series/Microsoft-R-Server-Series)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=Microsoft%20R%20Server)

- - -

## Cloud Scale Analytics

### Azure Analysis Services
*An enterprise-grade data modeling engine in the cloud*

- [Overview](https://azure.microsoft.com/en-us/services/analysis-services/)
- [Blog](https://blogs.msdn.microsoft.com/analysisservices/)
- [Documentation](https://docs.microsoft.com/en-us/azure/analysis-services/)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=Azure%20Analysis%20Services)

### Azure Cosmos DB
*A globally distributed, multi-model NoSQL database service: key-value, graph, document (JSON)*

- [Overview](https://azure.microsoft.com/en-us/services/cosmos-db/)
- [Technical Overview](https://azure.microsoft.com/en-us/blog/a-technical-overview-of-azure-cosmos-db/)
- [Documentation](https://docs.microsoft.com/en-us/azure/cosmos-db/)
- Multi-Model APIs
  - [Apache Cassandra](https://docs.microsoft.com/en-us/azure/cosmos-db/cassandra-introduction)
  - [DocumentDB](https://docs.microsoft.com/en-us/azure/cosmos-db/documentdb-introduction)
  - [Graph (Gremlin, TinkerPop)](https://docs.microsoft.com/en-us/azure/cosmos-db/graph-introduction)
  - [MongoDB](https://docs.microsoft.com/en-us/azure/cosmos-db/mongodb-introduction)
  - [Table (key-value)](https://docs.microsoft.com/en-us/azure/cosmos-db/table-introduction)
- [Query Cheat Sheets](https://docs.microsoft.com/en-us/azure/cosmos-db/query-cheat-sheet)
- [Frequently Asked Questions](https://docs.microsoft.com/en-us/azure/cosmos-db/faq)
- [Consistency Levels](https://docs.microsoft.com/en-us/azure/cosmos-db/consistency-levels)
- [Serverless Database Computing](https://docs.microsoft.com/en-us/azure/cosmos-db/serverless-computing-database)
- [Capacity Planner](https://www.documentdb.com/capacityplanner)
- [Local Emulator](https://docs.microsoft.com/en-us/azure/cosmos-db/local-emulator)
- [Database Migration Tool](https://docs.microsoft.com/en-us/azure/documentdb/documentdb-import-data)
- [GitHub Repository](https://github.com/CosmosDB)
- [Workshop Labs](https://cosmosdb.github.io/labs/)
- [Hands-On Lab](https://github.com/Microsoft/developer-immersion-data/blob/master/labs/awbexperience4/story_a_cosmosdb/Intro.md)
- [DocumentDB Query Playground](https://www.documentdb.com/sql/demo)
- [DocumentDB 10 GitHub Samples](https://azure.microsoft.com/en-us/blog/10-github-samples-with-azure-documentdb-you-shouldn-t-miss/)
- [Free Course on edX](https://www.edx.org/course/developing-planet-scale-applications-microsoft-dat237x)
- e-books:
   - [Guide to NoSQL with Azure Cosmos DB](https://azure.microsoft.com/en-us/resources/guide-to-nosql-with-azure-cosmos-db/en-us/)
   - [Microsoft Azure Cosmos DB Revealed: A Multi-Modal Database Designed for the Cloud](https://read.amazon.com/kp/embed?asin=B077G9STX2&preview=newtab&linkCode=kpe&ref_=cm_sw_r_kb_dp_lrYfFb9ERFY55) - by José Rolando Guay Paz
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=cosmos%20DB)

### Azure Database for MariaDB
*An enterprise-ready, fully managed community MariaDB*

- [Overview](https://azure.microsoft.com/en-us/services/mariadb/)
- [Documentation](https://docs.microsoft.com/en-us/azure/mariadb/)

### Azure Database for MySQL
*An enterprise-ready, fully managed community MySQL*

- [Overview](https://azure.microsoft.com/en-us/services/mysql/)
- [Documentation](https://docs.microsoft.com/en-us/azure/mysql/)

### Azure Database for PostgreSQL
*An enterprise-ready, fully managed community PostgreSQL*

- [Overview](https://azure.microsoft.com/en-us/services/postgresql/)
- [Documentation](https://docs.microsoft.com/en-us/azure/postgresql/)

### Azure Databricks
*A fast, easy, and collaborative Apache Spark-based analytics platform*

- [Overview](https://azure.microsoft.com/en-us/campaigns/databricks/)
- [Technical Overview](https://azure.microsoft.com/en-us/blog/a-technical-overview-of-azure-databricks/)
- [Databricks Blog](https://databricks.com/blog/)
- [Microsoft Blog](https://azure.microsoft.com/en-us/blog/tag/azure-databricks/)
- [Documentation](https://docs.microsoft.com/en-us/azure/azure-databricks/)
- [Knowledge Base](https://docs.microsoft.com/en-us/azure/databricks/kb/)
- [Product News](https://databricks.com/product/azure-product-news)
- [Frequently Asked Questions](https://docs.microsoft.com/en-us/azure/azure-databricks/frequently-asked-questions-databricks)
- [Databricks Academy](https://academy.databricks.com/)
- [Reference Architectures](https://azure.microsoft.com/en-us/blog/implementation-patterns-for-big-data-and-data-warehouse-on-azure/)
  - [Modern Data Warehouse](https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/articles/modern-data-warehouse)
  - [Real-Time Analytics](https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/articles/real-time-analytics)
  - [Advanced Analytics](https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/articles/advanced-analytics-on-big-data)
- Guides
  - [Apache Spark](https://docs.microsoft.com/en-us/azure/databricks/getting-started/spark/)
  - [Best Practices](https://github.com/Azure/AzureDatabricksBestPractices/blob/master/toc.md)
  - [Delta Lake](https://docs.microsoft.com/en-us/azure/databricks/delta/delta-intro)
  - [Machine Learning](https://docs.microsoft.com/en-us/azure/databricks/applications/machine-learning/)
  - [Deep Learning](https://docs.microsoft.com/en-us/azure/databricks/applications/deep-learning/)
  - [MLflow](https://docs.microsoft.com/en-us/azure/databricks/applications/mlflow/)
  - [Structured Streaming](https://docs.microsoft.com/en-us/azure/databricks/spark/latest/structured-streaming/)
- Tutorials
  - [Perform ETL Operations, Load Into SQL-DW](https://docs.microsoft.com/en-us/azure/azure-databricks/databricks-extract-load-sql-data-warehouse)
  - [Use Cosmos DB Service Endpoint](https://docs.microsoft.com/en-us/azure/azure-databricks/service-endpoint-cosmosdb)
  - [Stream Data Using Event Hubs](https://docs.microsoft.com/en-us/azure/azure-databricks/databricks-stream-from-eventhubs)  
- Learning Paths
  - [Data Engineering with Azure Databricks (new)](https://docs.microsoft.com/en-us/learn/paths/data-engineer-azure-databricks/)
  - [Perform Data Engineering with Azure Databricks](https://docs.microsoft.com/en-us/learn/paths/data-engineering-with-databricks/)
  - [Perform Data Science with Azure Databricks (new)](https://docs.microsoft.com/en-us/learn/paths/perform-data-science-azure-databricks/)
  - [Extract Knowledge & Insights from Your Data with ADB](https://docs.microsoft.com/en-us/learn/paths/data-science/)
- [Integration with Azure ML Service](https://github.com/Azure/MachineLearningNotebooks/tree/master/how-to-use-azureml/azure-databricks)
- [Microsoft ML for Apache Spark](http://aka.ms/spark)
- [Connector to IDEs](https://docs.microsoft.com/en-us/azure/databricks/dev-tools/databricks-connect)
- [Example Notebooks](https://databricks.com/resources/type/example-notebook)
- Example Pipelines - [Anomaly Detection](https://github.com/devlace/azure-databricks-anomaly), [Recommendation System](https://github.com/devlace/azure-databricks-recommendation)
- [Free eBooks](https://databricks.com/resources/type/ebooks)
- [On-Demand Webinars](https://databricks.com/resources/type/webinars/)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=databricks&lang-en=true)

### Azure Data Catalog
*A tool to register, enrich, discover, understand, and consume data sources*

- [Overview](https://azure.microsoft.com/en-us/services/data-catalog/)
- [Documentation](https://docs.microsoft.com/en-us/azure/data-catalog/)
- [Frequently Asked Questions](https://docs.microsoft.com/en-us/azure/data-catalog/data-catalog-frequently-asked-questions)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=Data%20Catalog)

### Azure Data Explorer
*A fast and highly scalable data exploration service*

- [Overview](https://azure.microsoft.com/en-us/services/data-explorer/)
- [Documentation](https://docs.microsoft.com/en-us/azure/data-explorer/)
- [Query Language](https://docs.microsoft.com/en-us/azure/kusto/query/)
- [Data Ingestion Overview](https://docs.microsoft.com/en-us/azure/data-explorer/ingest-data-overview)
- [Blog Post: Technology 101](https://azure.microsoft.com/en-us/blog/azure-data-explorer-technology-101/)

### Azure Data Factory
*A globally deployed data movement, orchestration, scheduling, and monitoring service*

- [Overview](https://azure.microsoft.com/en-us/services/data-factory/)
- [Blog](https://azure.microsoft.com/en-us/blog/tag/azure-data-factory/)
- [Documentation](https://azure.microsoft.com/en-us/documentation/services/data-factory/)
- [Frequently Asked Questions](https://docs.microsoft.com/en-us/azure/data-factory/data-factory-faq)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=Data%20Factory)

### Azure Data Lake
*A distributed storage and analytics service that scales dynamically*

- [Overview](https://azure.microsoft.com/en-us/solutions/data-lake/)
- [Blog](https://blogs.msdn.microsoft.com/azuredatalake/)
- [GitHub Repo](https://github.com/Azure/AzureDataLake)
- [Data Lake Store Documentation](https://azure.microsoft.com/en-us/documentation/services/data-lake-store/)
- [Data Lake Analytics Documentation](https://azure.microsoft.com/en-us/documentation/services/data-lake-analytics/)
- [Walkthrough: Scalable Data Science](https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/data-lake-walkthrough)
- [Video Series](https://channel9.msdn.com/Series/AzureDataLake)
- [Introducing U-SQL](http://usql.io/)
- [U-SQL Language Reference](https://msdn.microsoft.com/en-US/library/azure/mt591959(Azure.100).aspx)
- [AdlCopy Tool](https://azure.microsoft.com/en-us/documentation/articles/data-lake-store-copy-data-azure-storage-blob/)
- [Tools for Visual Studio](https://azure.microsoft.com/en-us/documentation/articles/data-lake-analytics-data-lake-tools-get-started/)
- [Online Training - MVA](https://azure.microsoft.com/en-us/blog/online-training-for-azure-data-lake/)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=Azure%20Data%20Lake)

### Azure Event Hubs
*A cloud-scale telemetry ingestion from websites, apps, and devices*

- [Overview](https://azure.microsoft.com/en-us/services/event-hubs/)
- [Documentation](https://azure.microsoft.com/en-us/documentation/articles/event-hubs-overview/)
- [Frequently Asked Questions](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-faq)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=event%20hubs)

### Azure HDInsight
*A managed Apache Hadoop, Spark, Storm, HBase, and R cloud service*

- [Overview](https://azure.microsoft.com/en-in/services/hdinsight/)
- [Blog](https://blogs.msdn.microsoft.com/azuredatalake/)
- [Documentation](https://azure.microsoft.com/en-us/documentation/services/hdinsight/)
- [Frequently Asked Questions](https://hdinsight.github.io/)
- [Developer Guide (pdf)](https://github.com/hdinsight/hdinsight-dev-guide/blob/master/HDInsight%20Developer%20Guide.pdf)
- [Apache Hive, Interactive](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-use-interactive-hive)
- [Apache Pig](https://azure.microsoft.com/en-us/documentation/articles/hdinsight-use-pig/)
- [Apache Kafka](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-kafka-introduction)
- [Apache Storm](https://azure.microsoft.com/en-us/documentation/articles/hdinsight-storm-overview/)
- [Apache Spark](https://azure.microsoft.com/en-us/documentation/articles/hdinsight-apache-spark-overview/)
- [Apache HBase](https://azure.microsoft.com/en-us/documentation/articles/hdinsight-hbase-overview/)
- [Apache Solr](https://azure.microsoft.com/en-us/documentation/articles/hdinsight-hadoop-solr-install-linux/)
- [Apache Giraph](https://azure.microsoft.com/en-us/documentation/articles/hdinsight-hadoop-giraph-install-linux/)
- [Microsoft R Server](https://azure.microsoft.com/en-us/documentation/articles/hdinsight-hadoop-r-server-overview/)
- [Presto](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-install-presto)
- [Hue](https://azure.microsoft.com/en-us/documentation/articles/hdinsight-hadoop-hue-linux/)
- [Tools & Samples GitHub Repo](https://github.com/hdinsight)
- [Microsoft Machine Learning for Spark](https://github.com/Azure/mmlspark)
- [Comprehensive Guide](https://azure.microsoft.com/en-us/blog/get-up-to-speed-with-azure-hdinsight-the-comprehensive-guide/)
- [Free eBook on HDInsight](https://blogs.msdn.microsoft.com/microsoft_press/2014/05/27/free-ebook-introducing-microsoft-azure-hdinsight/)
- [edX.org XSeries Program](https://www.edx.org/xseries/microsoft-azure-hdinsight-big-data-analyst)
- [Tools for Visual Studio](https://azure.microsoft.com/en-us/documentation/articles/hdinsight-hadoop-visual-studio-tools-get-started/)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=hdinsight)

### Azure IoT
*Cloud services to connect, monitor, and manage billions of IoT assets*

- [Azure IoT Overview](https://azure.microsoft.com/en-us/overview/iot/)
- [Blog](https://azure.microsoft.com/en-us/blog/topics/internet-of-things/)
- [Awesome Azure: IoT](https://github.com/Azure/iot)
- [IoT School](https://iotschool.microsoft.com/learning-paths)
- [IoT Solution Accelerators](https://azure.microsoft.com/en-us/features/iot-accelerators/)
- [IoT DevKit](https://microsoft.github.io/azure-iot-developer-kit/)
- [IoT Central Overview](https://azure.microsoft.com/en-us/services/iot-central/)
- [IoT Central Documentation](https://docs.microsoft.com/en-us/azure/iot-central/)
- [IoT Hub Overview](https://azure.microsoft.com/en-us/services/iot-hub/)
- [IoT Hub Documentation](https://docs.microsoft.com/en-us/azure/iot-hub/)
- [IoT Edge Overview](https://azure.microsoft.com/en-us/services/iot-edge/)
- [IoT Edge Documentation](https://docs.microsoft.com/en-us/azure/iot-edge/)
- [AI Toolkit for IoT Edge](https://github.com/Azure/ai-toolkit-iot-edge)
- [Developer Center](https://azure.microsoft.com/en-us/develop/iot/)
- [Hands on Labs](https://github.com/Azure-Samples/azureiotlabs)
- [Certified IoT Devices](https://catalog.azureiotsuite.com/)
- [edX MOOC: Developing IoT Solutions with Azure IoT](https://www.edx.org/course/developing-iot-solutions-azure-iot-microsoft-dev225x-0)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=iot&lang-en=true)

### Azure Redis Cache
*A secure, managed, dedicated Redis cache*

- [Overview](https://azure.microsoft.com/en-us/services/cache/)
- [Documentation](https://docs.microsoft.com/en-us/azure/redis-cache/)
- [Frequently Asked Questions](https://docs.microsoft.com/en-us/azure/redis-cache/cache-faq)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=redis%20cache)

### Azure SQL Database
*A managed cloud database for app developers*

- [Overview](https://azure.microsoft.com/en-us/services/sql-database/)
- [Documentation](https://docs.microsoft.com/en-us/azure/sql-database/)
- [Elastic DB Features](https://azure.microsoft.com/en-us/documentation/learning-paths/sql-database-elastic-scale/)
- [Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=azure%20sql%20database)

### Azure SQL Data Warehouse
*An elastic data warehouse as a service with enterprise-class features*

- [Overview](https://azure.microsoft.com/en-us/services/sql-data-warehouse/)
- [Blog](https://azure.microsoft.com/en-us/blog/tag/azure-sql-data-warehouse/)
- [Documentation](https://azure.microsoft.com/en-us/documentation/services/sql-data-warehouse/)
- [PolyBase Guide](https://azure.microsoft.com/en-us/documentation/articles/sql-data-warehouse-load-polybase-guide/)
- [sqlcmd Utility](https://msdn.microsoft.com/library/ms162773.aspx)
- [Automatic Scaling Template](https://github.com/Microsoft/sql-data-warehouse-samples/tree/master/arm-templates/sqlDwAutoScaler)
- [PowerShell Commandlets & REST APIs](https://azure.microsoft.com/en-us/documentation/articles/sql-data-warehouse-reference-powershell-cmdlets/)
- [DWU Calculator](http://dwucalculator.azurewebsites.net/)
- [edX.org Course](https://www.edx.org/course/delivering-data-warehouse-cloud-microsoft-dat220x)
- [Query from Visual Studio](https://azure.microsoft.com/en-us/documentation/articles/sql-data-warehouse-query-visual-studio/)
- [Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=sql%20data%20warehouse)

### Azure Stream Analytics
*A fully managed, SQL-based, real-time event processing engine*

- [Overview](https://azure.microsoft.com/en-us/services/stream-analytics/)
- [Blog](https://blogs.msdn.microsoft.com/streamanalytics/)
- [Documentation](https://azure.microsoft.com/en-us/documentation/services/stream-analytics/)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=stream%20analytics)

### Azure Time Series Insights
*A fully managed analytics, storage, and visualization service to explore and analyze IoT events*

- [Overview](https://azure.microsoft.com/en-us/services/time-series-insights/)
- [Documentation](https://docs.microsoft.com/en-us/azure/time-series-insights/time-series-insights-overview)
- [Portal](https://insights.timeseries.azure.com/)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=time%20series%20insights)

### Microsoft Power BI
*A suite of business analytics tools to analyze data, create visualizations and share insights*

- [Overview](https://powerbi.microsoft.com/en-us/)
- [Blog](https://powerbi.microsoft.com/en-us/blog/)
- [Documentation](https://powerbi.microsoft.com/en-us/documentation/powerbi-landing-page/)
- [Guided Learning](https://powerbi.microsoft.com/en-us/guided-learning/)
- [edX.org Course](https://www.edx.org/course/analyzing-visualizing-data-power-bi-microsoft-dat207x-3)
- [Custom Visuals Gallery](https://app.powerbi.com/visuals/)
- Power BI Desktop
  - [Overview](https://powerbi.microsoft.com/en-us/desktop/)
  - [Documentation](https://powerbi.microsoft.com/en-us/documentation/powerbi-desktop-get-the-desktop/)
  - [Create Visuals Using R](https://powerbi.microsoft.com/en-us/documentation/powerbi-desktop-r-visuals/)
  - [Use R in Query Editor](https://powerbi.microsoft.com/en-us/documentation/powerbi-desktop-r-in-query-editor/)
- Power BI Embedded
  - [Overview](https://azure.microsoft.com/en-us/services/power-bi-embedded/)
  - [Documentation](https://azure.microsoft.com/en-us/documentation/services/power-bi-embedded/)
- Power BI Report Server
  - [Overview](https://powerbi.microsoft.com/en-us/report-server/)
  - [Documentation](https://powerbi.microsoft.com/en-us/documentation/reportserver-get-started/)
- Power BI Service
  - [Overview](https://powerbi.microsoft.com/en-us/features/)
  - [Documentation](https://powerbi.microsoft.com/en-us/documentation/powerbi-service-basic-concepts/)
  - [REST API Documentation](https://msdn.microsoft.com/en-us/library/dn877544.aspx)
- [Channel 9 Videos](https://channel9.msdn.com/Search?term=Power%20BI)
