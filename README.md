# Solo.jar Library Framework lasted version
Doc: https://huosokkheang.github.io/Solo-Framework

1. make directory lib
2. move or copy file Solo.jar to lib directory
3. add this line into build.gradle 
   - implementation fileTree(dir: 'lib', include: ['*.jar'])
4. refresh gradle
5. Done
