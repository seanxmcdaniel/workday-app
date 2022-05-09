# Workday Scheduler Application

![Screenshot (28) - Copy](https://user-images.githubusercontent.com/102200863/167331771-a78ce989-e6d7-4eb7-9c11-b179b8fcfe5c.png)

For this week's challenge, I developed a workday scheduling application from starter code. The application allows you to type descriptions of 
upcoming events in each time block, and then save them to the application's local storage. After saving, when you refresh the page the saved 
events will still show on the page. Each time block will be red for the current hour, green for future hours, and gray for past hours. My workday 
scheduler utilizes HTML, CSS, Javascript, JQuery, and Bootstrap. !

## Saving Data to Local Storage

[Screenshot (29) - Copy](https://user-images.githubusercontent.com/102200863/167332172-03cf948c-e232-4eae-9e7a-fce426cc924f.png)

The screenshot above shows an event listener on the save button for setting the content (".description") of each time block to local storage. Once 
you hit the blue save button on the time block, the content of that time block will be set to local storage and when you refresh the page, the content 
will still show. 

## Past, Present, Future 

![Screenshot (29)](https://user-images.githubusercontent.com/102200863/167332597-d79a680c-2596-4e94-a870-e850141727bd.png)

Here you can see the function for looping through the time blocks and also the conditionals for changin the time block colors based on whether the event 
has passed, is currently happening, or is set to happen in the future. If the current hour is greater than the time on the time block, then the event has 
passed and will show as gray. If the current hour is equal to the time on the time block, then the event is currently happening within the hour and the 
time block will show as red. If the time is neither greater or equal, then it is less meaning the event has not happened yet and the time block will be 
green. 

## Local Storage 

![Screenshot (30) - Copy](https://user-images.githubusercontent.com/102200863/167333396-1f9b5fae-c6c5-4bab-ab09-118cec4f4a97.png)

This will load the value of each ".description" in individual time blocks that have been saved into the local storage.

### Deployed Application

Link: 

