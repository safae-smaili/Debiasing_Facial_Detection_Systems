# Debiasing_Facial_Detection_Systems

This was on of the MIT-guided project
this porjects explaine the fundamentals and provided some build functions, and you needed to complete the code .

It was a very exciting project. The cool part is the "debiasing system" that teaches you how to make the model learn objects in general without relying on the data to match.

One of the ways is using Variational Autoencoders. This VAE encoder in sample terme is generate a vectors of means and a vector of the data instead of the same data, which makes it more powerful in classification tasks.

So the diffrence between using CNN or a VAE encoder for detecting faces is that with CNN if we don't have faces with hates or dark colors on the data our model will not be capabale to predicte this faces after the training but with VAE the model kow what is a face and can generate faces with the most important object in the face that what make it detecte a darck face or face with hate or glasses without seeing them befor.

we can't use Debaising systems on every tasks but in the tasks that we need general classification like this one it will be a greate tool to do the work
