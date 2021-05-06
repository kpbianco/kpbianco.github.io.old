# Project overview

We are making an app to make hobby tracking and learning simpiler. The features that we want to add to the app is a calender that shows your progress of how you are doing in your hobbies. Then a timer that tracks your progress for the calendar. The main feature of the app is the ability to learn more about the hobbies you are interested in and find new ones.

# Key Architectural Drivers

We want the user experience to be simple to the user whenever they use the app. This means that the user data is syned across all the deives that they use to run the app. This is a very important issue for us because this means that the user expiernce won't suffer. 

# Architectural Style Choices

The arcitectures that we considered for the app were clinet server and peer to peer. Client server for us means that all the user data is stored in a centeral database and can be pulled up on any of the uesrs devices that are signed into their accouts. The other architecture that we considered for the app was peer to peer. The reason that we considered peer to peer was to possibly have less load on the server for the chat function. Since in this setup the users could be networked together with peer to peer networking and not have to go through a centereal server slowing things down. In the end we chose clinet server becuaes of the ease of developing and the simplicity to the user.

# Conclusion

I think that we made the right choice picking clinet server since it will be easier to develop with that model and the benefits to the user will be greater. Since it will be easy to sync the data across devices.

