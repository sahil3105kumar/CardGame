# CardGame
A project focused on making a game which will help people of our generation relive their childhood.


Rules:- 
This is a multiplayer game, which will allow user to play it with a friend far far away and too close too.

1.The player opens the app and is greeted with loading App animation.
2.User is asked to Login/SignUp. (Only if there isn't any account logged in)
3.The homepage displays the name of the game at the top and a lot of cards showing the type of card (E.g:- Superhero, Pokemon, Gods ...) to play or view.
4.The user can select any card to view the complete list.
4. In order to play, the user will be asked to create a room to invite friends.(At first it will handle two players, at later stage it will allow more).
5. The user will choose a card(only the room creator will choose the type).

The game progresses as follows.
Each player gets a random card from the same type. All cards will have similar stat types.
A random person will be choosen as leader of the first turn.
He/She will choose a stat to compare, the one with bigger(or smaller depending on the type of stat) will be choosen as winner and will get a point.
It will be the winner's turn next.
The player to reach 20 points first will win.(We can also add the option to choose how much points to achieve in order to win)


At later stage, we will start with each player having a set amount of card.
The card used will be sent below the stack of cards.
The winner will get the card of the looser and will be sent below the stack(it will be sent after his own card).
The first to loose all cards, loses.

In more developing phase, we can allow multiple player in a room and the rules will be same.
In more than 2 players, the game will continue until one player has all the cards or he is the only player in the room.
We can also add voice chat for more fun.

The project will be developed in different phases.
Phase 1: The User Interface (UI)

Think of this as building the exterior shell and planning the layout of our house.

    Goal: To build all the screens, buttons, forms, and visual elements that the user will see and interact with.
    Focus: Making the app look and feel right, ensuring navigation flows correctly from screen to screen (even if the buttons don't do anything real yet).
    Key Technology: Primarily focused on learning and using Jetpack Compose (UI) to build our interfaces.
    What's NOT included: Connecting to a real database, saving user data, complex logic, or integration with a backend. Buttons might just print a message or navigate to another screen placeholder.
    Analogy: Getting the walls up, the windows in, the doors hung, and deciding where the rooms will be. You can walk through the house, but there's no electricity or water.

  This phase is excellent for getting comfortable with Android UI development using Compose! Many initial tasks will involve creating individual UI components     or entire screens based on the design (which is coming soon!). You can often work on these pieces in isolation using previews.


Phase 2: Core Architecture and Logic

This is like putting in the internal structure, walls, and the pathways for utilities (but not connecting them yet).

    Goal: To build the internal systems that make the UI work and handle the app's logic and data flow, even if using fake (mocked) data initially.
    Focus: How different parts of the app communicate, managing the state of the UI (what data is shown), and implementing the app's core rules.
    Key Concepts: State Management, Navigation (Compose Navigation will cover navigation basics, but this phase applies it), separating UI from logic (often using patterns like ViewModels), and setting up ways to handle data (like using Mock Repositories that simulate getting data without a real backend).
    What's NOT included: Connecting to the actual Firebase (Backend) database. We'll use fake data sources to simulate the backend.
    Analogy: Building the internal walls, putting in the structural beams, and laying the pipes and electrical conduits inside the walls, ready to be connected later.

In this phase, we start connecting the beautiful UI built in Phase 1 to underlying logic. Tasks here might involve setting up how a screen gets the data it needs to display, or how a button press triggers a specific action within the app's logic layers.


Phase 3: Backend Integration

This is where we connect the utilities – water, electricity, and gas – to the system we've built.

    Goal: To connect the app's internal architecture to the real backend service (Firebase (Backend)).
    Focus: Sending and receiving real data from the database, handling user authentication (login/signup), and implementing features that require server-side interaction.
    Key Technology: Integrating with Firebase (Backend).
    What it enables: The app becomes fully functional, saving data persistently and allowing real users to interact with each other's information (e.g., seeing an event another host created).
    Analogy: Connecting the internal pipes and wires to the external water supply and power grid. The house becomes fully functional with running water and electricity.

This is often the phase where the app truly comes alive, dealing with real-world data and the complexities that come with it (like network issues, data security, etc.).
