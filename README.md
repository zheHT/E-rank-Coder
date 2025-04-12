RESOURCES:

Link to Canva
[Canva Presentation](https://www.canva.com/design/DAGkT3cR3HE/7cYvOqkTlmrHFDHukjnYFw/view?utm_content=DAGkT3cR3HE&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hded7ee9a4e)

Link to Figma Prototype
[Figma Prototype](https://www.figma.com/proto/fHHT9GI2Qo2nTcWYlWQj0l/Hackathon?node-id=0-1&t=9sn3DwWdKarQX2LW-1)

Link to Figma Prototype (Dev Mode)
[Figma DevMode](https://www.figma.com/design/fHHT9GI2Qo2nTcWYlWQj0l/Hackathon?node-id=0-1&m=dev&t=lwGrGjLxToHCud8l-1)

INSTRUCTIONS AND NOTES:

1. Figma Prototype

- The first link of Figma directs you to the prototype presentation mode. In this mode, several icons are interactable, so feel free to check out
- To know which icon is interactable, click anywhere on the frame, and it will indicate which icons is responsive
- Dev Mode shows overall structure of interfaces
- In the GitHub repository, there is also a PDF form for the Figma Interfaces

2. Canva Slide

- Link to Canva will direct you to Team E-Rank Coders' presentation slides on UM Hackathon Domain 2 - Quantitative Trading

3. Codes (Both .py and .ipynb)

- TAKE NOTE: do make sure your device have the library imported by the code, if device does not have a certain library, do run !pip install (library_name_without_brackets)
- If running the program on Google Colab (in .ipynb form), do Runtime -> Run all / Ctrl + F9
- Part of the codes could be modified, for example API_KEY, base_url and endpoint could be changed according to other source if trying to retrieve Data from other data sets.
- For file cryptoanalyzer, API_KEY could be modified in "main" function, endpoint and parameters could be modified in MainApp class, base_url and headers could be modified in DataRetriever class.
- For file s_rankcrptonewsanalyser, url could be modified in fetch_cypto_news function, if you want to modify api_key to access other source, please modify all the api_key in functions: fetch_crypto_news, generate_training_data, or in whatever calls to fetch_crypto_news (E.g. line 135)
- For file strategybuilder, API_KEY and BASE_URL could be modified on lines 18 and 19, to connect to other servers for datasets
  *do take note the code and Machine Learning model is still underdevelopment and experimental so many features are incomplete, the output might not be accurate
  *when accessing datasets, take note on endpoints and headers, as sometimes with the correcy api key, there will still be some failure in retrieving data, take note on errors to approach debugging, E.g. Error 401 - unauthorized access (api_key is wrong), Error 404 - source not found (URL / endpoints is wrong)

REFERENCES:
API

- CyboTrade API
- Coinglass Orderbook History API
- News API
- yFinance API

Libraries imported

- requests
- panda
- numpy
- hmm
- hmmlearn
- MinMaxScaler
- sklearn
- textblob
- matplotlib
