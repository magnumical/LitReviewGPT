# LitReviewGPT
A systematic way to extract info from papers

I assume you already have access to text, txt file, .doc, or .pdf file of the paper you are interested in. 


first essage to chatGPT will be:
```
Read this article completely and answer to my questions in the next message:
[paper material from METHODS to end]
```

Then, these questions can be asked (adjust based on purpuse of your paper)in the following format:

``` Read article carefully and pay attention to every detail. Tell me what authors wrote about:
[INFORMATION YOU ARE INQUIRING TO BE COPIED HERE]
I prefer exact sentence and quotation fro paper but you can also write me your understanding and summarization. I don't want you to write it yourself. answer in bullet points. Set your laziness to zero and read all texts. Be detailed in your answers. When mentioning study description, be detailed. when mentioned equipment or devices or techniques, write exact names and list (model name). You can be concise while answering. You don't need to form a sentence. it can be short and brief in terms of length, but include everything and comprehensive
```


```  Type of study (qualitative, quantitative)	,Number of participants	,Proposed system name	,Dataset name (if they don't have their own)	,what group is being targeted?	,Age range	,Fem/Male ratio,	 inclusion criteria	,Target problem	,Target variable	,Control Groupe? (0: NO, 1 Yes)	,IoT/M2M Technologies? (0: NO, 1 Yes),	Experiment description	,Experiment duration and # of trials	,Statistical method	,Application Area	,Equipments (devices/tools)	,Main Processor (e.g. device, or cloud)	,Evluation technique,```

```  channels to track users (sensors) Exact name of Channels (sensors, devices),  Data Types (physiological data, signals, surveys,... numbers, categorical,continous?)	Programming languages	Any App made? (web/android/ios)	Any feedback loop to users?	Personalization of system to users?	D2D ommunication Protocols? (can be sensor to devices or else, Bluetooth, http, ictp)	real-time system?	application?	Location to mount/wear wearable ```

``` EMG (Device/sampling frequency/Feature exctraction)	EMG electrodes	ECG (Device/sampling frequency/Feature exctraction)	EOG (Device/sampling frequency/Feature exctraction)	Accelerometer ACC	Blood Related	respiration	temperature	electrodermal activity EDA	Other signals?	detailed lsit of extracted features		Classification of what?	Classification model	Preprocessing?	Is there fusion of features?
for signals that hadn't been discusses, show NA. ```


```  Data encryption?	Any type of security measure	Authentication?	BC IAM mechanism (AuthN, AuthZ)	BC Platform (eth, hyperledger fabric, ripple, …)	Access policy (permissionless, permissionable)	Consensus protocol (PBFT, SOLO, PoW, kafka)	Cryptocurrency (0: no, 1: yes)	mining	Idm/ revokation	IdM model (trusted identity, NA)	Throughput	Latency	Security reqs	Data exchange (json?)	ML model security	ML model optimized for on-device?	Application (security, HER, PHR, RPMS, DSMS, m-health) for items that hadn't been discusses, show NA.```

``` Advantages	Drawbacks/Limitations (e..g, small sample size or anything else that they mentioned)	Future Works	New Findings(what were there findings? say by numbers and statistical analysis they have done)	Results	Conclusions ```

