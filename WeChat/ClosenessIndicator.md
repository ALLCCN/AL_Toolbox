# An indicator of closeness in WeChat

## input
- friends: array, a list of friends
- friend: object
- friend.hhh: int, the number of hhh/hahaha in the chat history
- friend.active: int, the number of active day in chat history during a period
- friend.cache: number, the size of cache in chat history in this phone

## output:
- friend.value: number, the value of indicator of closeness in WeChat

## explanation
- friend.hhh: shows the positive emotions in the chat history, higher the better
- friend.active: shows the frequency of chat in recent days, and the closeness of relationships in recent days
- friend.cache: shows the history of friendship, but will affect by some files and images in recent chat