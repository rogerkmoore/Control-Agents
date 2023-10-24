# Control Agents
 
A simulation (in Pure Data) of control agents operating in an environment consisting of an amount of 'stuff' that may be collected in a pile on the 'left' or on the 'right'.  A control agent is able to move the 'stuff' from left-to-right or right-to-left (using a PID controller) according to their configured settings in terms of intention, effort, attention and compliance.  Successful control is manifest as 'happy', whereas loss of control is manifest as 'sad'.  The environment can be subjected to various disturbances (manual, noise or ramp) which an agent may or may not be able to overcome depending on its settings.  

Multiple agents (created using copy-&-past) can operate in the same environment.  Their settings can be configured to facilitate competition (different intentions) or collaboration (same intentions).  

Audio vocalisations can be enabled which reflect the various internal parameters.

Note that [average.pd] is part of the [maxib] library of externals.  So when Pd is running, go to Help > Find externals.  Enter 'average' into the search window and click on 'Search'.  This should bring up the [maxlib] library; click on it to install.  You'll then need to ensure that this library can be found by Pd by adding it to Pd > Settings > Path.

You can find the slides from a talk featuring [Control Agents] [here](https://github.com/rogerkmoore/Talks/blob/main/2023%20-%20IAPCT/Moore%20-%20Compliance%20in%20perceptual%20control%20systems%20Insights%20and%20implications.pdf)