# car-game
Simple car game

command="""
while True:
    command=input(">").lower()
    if command == "start" :
        print("Car started...")
    elif command == "stop" :
        print("Car stopped.")
    elif command == "help" :
        print("""
            start-to start the car
            stop-to stop the car
            quit-to quit
        """)
    elif command == 'quit' :
       break
    else:
        print("Sorry,l don't understand that")
           
