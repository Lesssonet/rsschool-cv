<!-- Имя и фамилия
Контакты для связи
Краткая информация о себе (ваша цель и приоритеты, подчеркните свои сильные стороны, расскажите о своём опыте работы, если опыта работы нет, расскажите о своём стремлении учиться и узнавать новое)
Навыки (языки программирования, фреймворки, методологии, системы контроля версий и инструменты разработки, которыми вы владеете)
Примеры кода
Опыт работы. Junior Dev может перечислить учебные проекты с указанием использованных навыков и ссылками на исходный код.
Образование (включая пройденные курсы и тренинги)
Английский язык (уровень английского языка, если была языковая практика, расскажите о ней) -->
# Sergey Levsha
## Contacts 
- Phone: +7-909-234-21-56
- Telegram: @baymi423
- Discord: lesssonet
## About Myself
My goal is to reach end of the course. I wanna learn to code. I'm resposible person and really love planning everything. I didn't code since University. Work as a moderator in game dev studio.
## Skills 
HTML, CSS, JS, GIT
## Codewars task

>You are given two sorted arrays that contain only integers. These arrays may be sorted in either ascending or descending order. Your task is to merge them into a single array, ensuring that:
The resulting array is sorted in ascending order.
Any duplicate values are removed, so each integer appears only once.
If both input arrays are empty, return an empty array.
 ```
 mergeArrays(arr1, arr2) {
  let arrSorted = arr1.concat(arr2).sort((a,b)=>a-b);
  for (let i = 0; i < arrSorted.length; i++){
    let rep = arrSorted[i];
    console.log(i);
    if (rep == arrSorted[i + 1]) { arrSorted.splice(i, 1)}
      console.log(arrSorted);

//     return arrSorted
  }
  console.log(arrSorted);
  return arrSorted
} 
```
## Education
Bachelor of the DSTU. Computer Science.
## English
I think it's aroun intermediate. But in reality it's pre-intermediate.
