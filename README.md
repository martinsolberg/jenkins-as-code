# faggruppe2017
Repo for workshop i Jenkins, fagruppe Devops 05.04.2017

#Oppgaver#

Vi tar utgangspunkt i declarative pipeline først - mulig å prøve seg på scripted etterpå

1) Lag en 'Hello World' Jenkinsfil	
	- Legg Jenkinsfile på øverste nivå i repo
	- Følgende _må_ være på plass:
		- 'pipeline' - direktiv
		- 'agent'
		- 'stages'
		- 'stage'
		- 'steps'
		- Minst ett steg - prøv for eksempel 'sh' som kjører et shell-script (bash by default)
	- Lag din personlige branch, sjekk inn i repo og push til github (hvis du har github)
		- (git checkout -b DIN_BRANCH)
		- Har du ikke github, kan du lime pipelinekoden direkte inn i en pipelinejobb i Jenkins
	- Opprett en pipeline-jobb i Jenkins 
	- Hvis du har pushet til github, sett opp git-repo med https og riktig branch
	- Hvis du ikke har pushet til github, lim pipelinekoden din inn i editoren
	- Kjør og se hva som skjer.
	- Du kan 'linte' jenkinsfila di ved å kjøre 
		- curl -X POST -F "jenkinsfile=<Jenkinsfile" http://faggruppejenkins.northeurope.cloudapp.azure.com/pipeline-model-converter/validate

