# Onsdag-Vecka-1-exercise01for-the-secund-time-


Exercise 1: Create environments
skapa två environments i repo settings, dev och prod
lägg in environment rules så att prod kräver en reviewer innan deploy
gör en dummy workflow som bara printar “deploy to ${{ github.environment }}”

Exercise 2: Add secrets
skapa en API key som Secret i dev environment
i workflow, läs den som secrets.MY_API_KEY och echo maskad value i körningen
visa hur output:en ser ut i Actions log

Exercise 3: Repository variables
lägg in en repo variable kallad SERVICE_NAME
uppdatera workflow så att det skriver ut
 deploying: ${{ vars.SERVICE_NAME }}
ändra värdet i GitHub UI och kör om workflow

Exercise 4: Environment specific behavior
skapa ett workflow som triggas på push i main
om branch är main → deploy to prod environment
om branch är annan → deploy to dev environment


testing main deploy

Commit directly to main 

