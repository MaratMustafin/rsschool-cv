# Мустафин Марат
![Graaaavaaaatar](https://www.gravatar.com/avatar/sampplayer2@gmail.com?d=identicon&s=128)
---
## Контакты
 __Telegram:__ [@apofsys](https://t.me/@apofsys)
 __GMAIL:__ sampplayer2@gmail.com
 __GITHUB:__[MaratMustafin](https://github.com/MaratMustafin)
## Моя мотивация
Моя задача - пройти курсы от школы RS School, желаю себе удачи. Для меня важно сделать нормальный график, чтобы успевать все учить! Хочу выучить __JavaScript__, потому что обладаю плавающими знаниями. 
## Технический опыт
1. Language:__Ruby,Python__
2. Frameworks:__Flask__
3. Методологии:__функциональное программирование__
4. контроль версий:__git__ 
5. инструменты: __vs code__
## Последний рабочий код
```python
@app.route('/invite',methods=['POST'])
def invite():
    name = request.form['name']
    phone = request.form['phone']
    email = request.form['email']

    if name and phone and email:
        try:
            wisher = Wisher(name=name,phone=phone,email=email)
            db.session.add(wisher)
            db.session.commit()
            newName = name
            return jsonify({'name':newName,'message':'Ожидайте с вами обязательно свяжутся! А пока вы можете оплатить за обучение'})
        except sqlalchemy.exc.IntegrityError:
            return jsonify({'error':'Пользователь с такой почтой уже существует'})
    return jsonify({'error'})
```
## Опыт в программировании
5. тырю материалы и создаю свой макаронный код =)
## Обучение
| Университет | Специализация |Год |
| ------ | ------ | ------ |
| унив. им. С.Сейфуллина | Информационные системы | 2017-2021|

| Онлайн курсы | Курсы |
| ------ | ------ |
| Udemy | Python Flask Bootcamp |
## Опыт английского языка
В основном люблю читать на русском,а слушать английские песни
Мой уровень английского это __A1__
