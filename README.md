# Covid19_classification_tmempr

In order to run the codes in the Train&Test section, the path of the files with extensions csv. in the DataSet_csv folder must be changed on the code.

Example for tmempr:
covid_list = pd.read_csv("yourPath/DataSet_Csv/covid_tmempr_100.csv", sep=','  , engine='python')
normal_list = pd.read_csv("yourPath/DataSet_Csv/normal_tmempr_100.csv", sep=','  , engine='python')

Example for dct(Discrete Cosine Transform) :
covid_list = pd.read_csv("yourPath/DataSet_Csv/covid_dct_100.csv", sep=','  , engine='python')
normal_list = pd.read_csv("yourPath/DataSet_Csv/normal_dct_100.csv", sep=','  , engine='python')

In order to run preprocessing codes, you must edit the following codes as in the example.

covid_list_folder = os.listdir("yourPath/DataSet_Orginal/Covid")
normal_list_folder = os.listdir("yourPath/DataSet_Orginal/Normal")

