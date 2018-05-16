# ActivityRecognition

## Android User Activity Recognition – Still, Walking, Running, Driving 

Detecting user activity in android can de done very easily using ActivityRecognitionClient. You can detect user activities like Still, Running, Walking, Cycling, Tilting, Driving etc., We can see this API widely used in lot of fitness apps (like GoogleFit) to provide user activity info like number steps he is taken, the distance he is travelled.

#### add service & permission inside manifest.xml file 

    <uses-permission android:name="com.google.android.gms.permission.ACTIVITY_RECOGNITION" />


<service
            android:name=".DetectedActivitiesIntentService"
            android:exported="false" />

        <service android:name=".BackgroundDetectedActivitiesService"></service>
        
        
        
#### add dependencies inside build.gradle file (app level)

dependencies {
   implementation 'com.android.support:design:27.1.1'
   
  implementation 'com.google.android.gms:play-services-location:11.6.0'
}


### Screen shot 

![whatsapp image 2018-05-04 at 2 51 47 pm](https://user-images.githubusercontent.com/24228143/39621814-a458590e-4fad-11e8-9fdf-298871c36eaf.jpeg)
![whatsapp image 2018-05-04 at 2 58 55 pm](https://user-images.githubusercontent.com/24228143/39621816-a4b6eb7c-4fad-11e8-9615-8f08e21936fa.jpeg)
![whatsapp image 2018-05-04 at 3 00 51 pm](https://user-images.githubusercontent.com/24228143/39621818-a4e80b58-4fad-11e8-99d4-21b01baa5621.jpeg)









