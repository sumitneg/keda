# keda
This Repository Test the Githubaction workflow to call a webHook which in turns creates a Event in Keda CLoudevent. 
The cloud event then in turn Drain the created event to PUB SUB 
Thevalue changed once pooled by Keda scaled object , start PA for scaling of NGINX POds drom 1 to 3.
