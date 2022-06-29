# Hvordan få tilgang til Slack som ekstern

Slacken til Miljødirektoratet har påkrevd SSO pålogging via Miljødirektoratet sin AAD hos Microsoft. For at eksterne skal få logget inn på Slack må man med andre ord ha en AD-bruker i Miljødirektoratet, og denne brukeren må være med i gruppen som heter slack-tilgang i AD.

Hvis du mangler bruker, les "Hvordan få AD-konto" nedenfor.

Hvis man allerede har bruker som er med i AD-gruppa:
1. Gå på https://miljodir.slack.com
2. Trykk på den store grønne knappen med tittel Sign in with Miljødirektoratet
3. Logg inn med AD-konto i Miljødirektoratet. For eksterne er mailen som skal benyttes på formatet ekstern_brukernavn@miljodir.no. (Obs: hvis du allerede er logget inn med en annen konto på Microsoft er det ikke sikkert du får muligheten til å logge inn med en annen konto. Gå isåfall på miljodir.slack.com i incognito mode, eller logg ut av den brukeren du allerede er innlogga med, og prøv igjen)
4. Så skal man være inne på Slack :tada:

## Hvordan få AD-konto

Teamansvarlige og prosjektledere kan bestille AD-kontoer for sine innleide medarbeidere/prosjektdeltakere. Dette gjøres ved å sende en epost til ithjelp@miljodir.no med "Devops" som første ord i subject. Eposten må inneholde følgende:
1. Fullt navn
2. Firma
3. epost
4. mobilnummer
5. startdato for engasjement
6. sluttdato (om den er kjent, hvis ikke settes den til maks ett år frem i tid)
7. ønskede tilganger (i dette tilfellet Slack)

## Kjøreregler for bruk av Miljødirektoratets Slack

- Ikke del persondata eller andre ting som er sensitive (f.eks. ting som er unntatt offentlighet) på Slack.
- Ikke del data som kan kompromittere sikkerheten, integriteten eller autentisitet til applikasjoner eller brukerne av dem på Slack. Typiske eksempler på slike ting er innloggingstokens, passord.
- Ikke bruk @ channel med mindre det strengt talt er nødvendig, da det gjør at alle i den kanalen det gjelder får en notification. Vurder hva som er relevant og viktig å vite om for hvem.
- Legg gjerne inn hvilket team du jobber i, hva du jobber med, og hvor du jobber i profilen din på Slack. Trykk på personikonet øverst til høyre :point_right: -Profile :point_right: Edit profile.
- Opprett gjerne en ny kanal for teamet ditt eller et tema du er interessert i, men sjekk gjerne om det fins en kanal for temaet fra før.

