# INSTALLATION

You can either use VPS or can use Codespace, it is totally depend upon you. If you use VPS, your node will be active all the time but if u use Codespace, your node will active until you close the codespace terminal

Open Codespace or Termius (If you are using VPS)

Use this command first to create a Screen session

sudo apt-get update
sudo apt-get install screen
screen -S Gaianet
   
   Then Paste this command :
         wget https://raw.githubusercontent.com/king00719/gaianet-node/main/script.sh && chmod +x script.sh && ./script.sh




To detach from screen session, Press Ctrl + A + D
Chat with that bot and increase your throughputs, It may take 1 hr to 2 hr to update throughputs
Also try to grab roles on Galxe
Notes for Codespace User
When you will close codespace, your node will also be stopped, so if u want to chat with your bot to increase throughputs, U first need to run the node again, so don't delete the existing codespace terminal, otherwise it will generate a new node ID

If u want to chat with the bot so u first need to open existing terminal, use gaianet start command to start your existing node. Then go to the bot link to chat
