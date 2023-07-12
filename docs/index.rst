.. image:: img/hydra_logo.png
  :alt: Hydra


Welcome to Hydra's documentation! **Hydra** is an extensible framework for training, managing and 
deploying machine learning models for real time data quality monitoring.

Check out the Github for further information.

.. grid:: 1

   .. grid-item-card:: User Interface
      :link: docs/labelerFE
      :link-type: doc
      :align: center

      How to interact with Hydra's web-based pages. 

.. grid:: 2

   .. grid-item-card:: HTML Pages
      :link: docs/labeler
      :link-type: doc

      The backend of Hydra's webpages.


   .. grid-item-card:: HTML Integrations
      :link: docs/getClassification
      :link-type: doc

      The link between Hydra's backend and frontend.  

.. grid:: 2

   .. grid-item-card:: HTML Utils
      :link: docs/help
      :link-type: doc

      Background scripts for the frontend of Hydra.

   .. grid-item-card:: Hydra Libraries
      :link: docs/connectToDB
      :link-type: doc

      Background scripts for the backend of Hydra.

.. grid:: 2 

   .. grid-item-card:: Hydra Scripts
      :link: docs/schemaSync
      :link-type: doc

      The main scripts that run Hydra. 

   .. grid-item-card:: Hydra Utils
      :link: docs/dependencies
      :link-type: doc

      Different dependencies, configurations, and connections that Hydra uses. 


      



.. note::

   This project is under active development.


.. toctree::
   :hidden:
   :caption: 🧑User Interface

   labelerFE
   libraryFE
   hydraRunFE

.. toctree::
   :hidden:
   :caption: 📄HTML Pages

   labeler
   library
   hydraRun
   hydraRunHelp


.. toctree::
   :hidden:
   :caption: 🤖HTML Integrations

   getClassification
   getLeaderBoard
   getLog
   getModelsInfo
   getModels
   getPlotTypes
   getImages
   libraryUtils
   login
   pollRunTime
   populateSelectors  
   recordLabels
   subNewPlot


.. toctree::
   :hidden:
   :caption: 🖥️HTML Utils

   help
   label
   executeQuery&Database
   verifyExperiment


.. toctree::
   :hidden:
   :caption: 📚Hydra Libraries
   
   connectToDB
   aiReport
   dataPreprocessing
   inferenceEngine
   gradcam


.. toctree::
   :hidden:
   :caption: 📝Hydra Scripts  

   schemaSync
   startHydra
   hydraTrain
   hydraCleaner
   hydraFeeder
   hydraPredict
   hydraKeeper
   helpers
   imgCrawler
   runGradCAM
   modelAnalysis
   assignTrainWeights
   simulateRunTime

.. toctree::
   :hidden:
   :caption: 🔧Hydra Utils

   dependencies
   databaseConfig
   establishingDBConnection

