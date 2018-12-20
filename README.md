# android-MergeAAR
Merge all aar files  

I just want to merge all FUCKING aar files into one(such as exoplayer), If you want build all aar library from source, and put them into one aar file, you should check https://github.com/Vigi0303/fat-aar-plugin and https://github.com/adwiv/android-fat-aar.  

I don't maintain this project but if you'd like to, feel free to fork.   

Email:yihongyuelan@gmail.com  

Notice:  
1.distributionUrl=https\://services.gradle.org/distributions/gradle-2.14.1-all.zip  
If you use gralde 4.x , it will fail after you called gradle sync;  

2.classpath 'com.android.tools.build:gradle:2.2.3'  
Because fat-aar only support 2.x or 3.x, but if you want 3.x you should modify some code(I didn't do it :).  

3.Set android.enableBuildCache=false in gradle.properties  
DO NOT use cache, it will eat your cat :D  

4.In AndroidStudio, open gradle task and find :timaexo-build-assembleRlease  
If you like command line, just type ./gradlew :timaexo:assembleRelease  




Some improved repositories：  
https://github.com/CarGuo/android-fat-aar  
https://github.com/corelmax/android-fat-aar  
https://github.com/toBeNull/aar/blob/master/sdk/fat-aar.gradle  
