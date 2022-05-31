# Hvordan få tilgang til Slack som ekstern

Slacken til Miljødirektoratet har påkrevd SSO pålogging via Miljødirektoratet sin AAD hos Microsoft. For at eksterne skal få logget inn på Slack må man med andre ord ha en AD-bruker i Miljødirektoratet, og denne brukeren må være med i gruppen som heter slack-tilgang i AD.

Hvis du mangler bruker, les [denne confluence siden](https://miljodir.atlassian.net/wiki/spaces/DEVOPS/pages/2524840756/Bestilling#Ny-utvikler/-prosjektmedarbeider) for hvordan man får vedkommende inn i AD.

Hvis man allerede har bruker som er med i AD-gruppa:
1. Gå på https://miljodir.slack.com
2. Trykk på den store grønne knappen med tittel Sign in with Miljødirektoratet
3. Logg inn med AD-konto i Miljødirektoratet. For eksterne er mailen som skal benyttes på formatet ekstern_brukernavn@miljodir.no. (Obs: hvis du allerede er logget inn med en annen konto på Microsoft er det ikke sikkert du får muligheten til å logge inn med en annen konto. Gå isåfall på miljodir.slack.com i incognito mode, eller logg ut av den brukeren du allerede er innlogga med, og prøv igjen)
4. Så skal man være inne på Slack :tada:
