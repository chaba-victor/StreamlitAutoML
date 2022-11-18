# StreamlitAutoML

## Automated machine learning (AutoML)

Automated machine learning, often known as AutoML, is the practice of employing ML models to solve practical issues. It automates the selection, composition, and parameterization of machine learning models, to be more precise. Automating the machine learning process makes it more user-friendly and often provides faster, more accurate outputs than hand-coded algorithms. Machine learning is now more accessible to enterprises without dedicated data scientists or machine learning specialists, thanks to AutoML software platforms. These platforms can be bought from an outside provider, accessed through open source repositories like GitHub, or developed in-house.

### How AutoML process works

AutoML is normaly a platform that simplifies the steps involed in a machine learning process; handling a raw dataset to deploying a practical machine learning model. In traditional ML, models are hard coded, and each step in the process handled separately.

AutoML automatically locates and uses the optimal type of machine learning algorithm for a given task. It does this with two concepts:

- Neural architecture search, which automates the design of neural networks. This helps AutoML models discover new architectures for problems that require them.
- Transfer learning, in which pretrained models apply what they've learned to new data sets. Transfer learning helps AutoML apply existing architectures to new problems that require it.
Users with minimal machine learning and deep learning knowledge can then interface with the models through a relatively simple coding language like Python.

More specifically, here are some of the steps of the machine learning process that AutoML can automate, in the order they occur in the process:

- Raw data processing
- Feature engineering and feature selection
- Model selection
- Hyperparameter optimization and parameter optimization
- Deployment with consideration for business and technology constraints
- Evaluation metric selection
- Monitoring and problem checking
- Analysis of results


### Pros and cons of AutoML
The main benefits of AutoML are:

- Efficiency -- It speeds up and simplifies the machine learning process and reduces training time of machine learning models.
- Cost savings -- Having a faster, more efficient machine learning process means a company can save money by devoting less of its budget to maintaining that process.
- Accessibility -- Having a simpler process allows companies to save money on training staff or hiring experts. It also makes machine learning a viable possibility for a wider range of companies.
- Performance -- AutoML algorithms also tend to be more efficient than hand-coded models.
The main challenge of AutoML is the temptation to view it as a replacement for human knowledge. Like most automation, AutoML is designed to perform rote tasks efficiently with accuracy and precision, freeing up employees to focus on more complex or novel tasks. Things that AutoML automates, like monitoring, analysis and problem detection, are rote tasks that are faster if automated. A human should still be involved to assess and supervise the model, but no longer needs to participate in the machine learning process step-by-step. AutoML should help improve data scientist and employee efficiency, not replace them.

Another challenge is that AutoML is a relatively new field and some of the most popular tools are not yet fully developed.

### Different ways to use AutoML

utoML shares common use cases with traditional machine learning. Some of these include:

- Fraud detection in finance. It can improve the accuracy and precision of fraud detection models.
- Research and development in healthcare, where it can analyze large data sets and draw insights.
- Image recognition, which is useful for facial recognition.
- Risk assessment and management in banking, finance and insurance.
- Cybersecurity, where it can be used for risk assessment, monitoring and testing.
- Customer support, where it can be used for sentiment analysis in chatbots and to increase the efficiency of the customer support team.
- Malware and spam, where it can be used to generate adaptive cyberthreats.
- Agriculture, where it can be used to expediate the quality testing process.
- Marketing, where it can be used for predictive analytics and improved engagement rates. It can also be used to improve efficiency of behavioral marketing campaigns on social media.
- Entertainment, where it can be used as a content selection engine.
- Retail, where it can be used to improve profits and reduce waste/inventory carryover.

### AutoML tool features
Some popular AutoML platforms include:

Google AutoML, Google's proprietary, cloud-based automated machine learning platform.
Azure Automated Machine Learning, a proprietary, cloud-based platform.
Auto Keras, an open-source software library developed by the DATA lab at Texas A&M university.
Auto-sklearn, which evolved from and replaced Scikit learn, which was an open source, commercially usable collection of simple machine learning tools in Python. Users can find it on GitHub.
Auto-sklearn and Azure are generally considered cheaper because they are usually less resource-intensive than the other two models. They rely strongly on data they've already seen and known architectures, meaning they don't need the whole data set to work. They use classification and regression techniques to do this.

Google AutoML and AutoKeras, by contrast, are more adept at creating new models, but also are more resource intensive, as they require the whole data set normally. They use recurrent neural networks (RNN), convoluted neural networks (CNN) and long short-term memory (LSTM).
