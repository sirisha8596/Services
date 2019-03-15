# Services
A Service is an application component that can perform long-running operations in the background once we can start a service, and it
continues to run in the background even if the user switches to another.This App cantains two buttons click on START SONG button the music
will play by using MediaPlayer until the user can stop the music.The Music file stored in a raw directory.It cantains three methods onStartCommand(),onCreate(),onDestroy().the system calls onStartCommand() when another component, such as an activity, requests that the service.The system calls onCreate() when the service is first created using onStartCommand().
