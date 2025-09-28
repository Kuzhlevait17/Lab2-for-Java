Lab2-for-Java

Лабораторная работа 2. Вариант 6.
Выполняла: Кужлева Любовь ИТ-17-2024/ИКНТ/ЛА8-2024/ПР4-2024.

Данная работа разделена на 5 блоков, каждый из который реализован с помощью конструкции switch. 
Каждое задание имеет полное описание для вывода на экран. 
В классе Main реализована работа программы с дружественным интерфейсом.

Блок 1. Время и Дом.
Данный бллок разделен на два задания: Время и Дом.
В задании время необходимо было 



Блок 2. Сотрудники и отделы.
В данном задании необходимо создать нескольких сотрудников и вывести информацию о них в соответствии с их статусом (Сотрудник/Работодатель).
Для создания сотрудников используются приватные поля name, department, boss, а также конструкторы, позволяющие разграничивать сотрудника от работодателя. 
Для того, чтобы указать работодателя обычного сотрудника, используется сеттер. 
Также программа позволяет получить название отдела и фамилию сотрудника, а также проверить, является ли сотрудник работодателем.
Если сотрудник не является работодателем, необходимо установить его руководителя через соответствующий метод.
Проверка статуса сотрудника выполняется через метод isBoss(). 
Если сотрудник является работодателем, выводится соответствующее сообщение, в противном случае отображается информация о его руководителе.
Также используется метод toString(), который позволяет правильно вывести на экран статус сотрудника. 

Блок 3. Сотрудники и отделы(обновленная версия).
В данном задании необходимо было поменять код так, чтобы 

Блок 4. Строим дом.
В данном задании необходимо было переписать код задания 1 подзадания Дом так, чтобы выполнялось два условия.
Первое главное условие задачи - создание только путём указания количества этажей.
При попытке создания объекта класса через стандартный конструктор по умолчанию программа не дает создать.
Также недоступен сеттер.
<img width="1039" height="245" alt="image" src="https://github.com/user-attachments/assets/fa8d27c6-dc76-47d5-b171-13b52cb0fb4c" />
Второе главное условие задачи - нельзя поменять количество этажей. Данное условие реализуется с помощью final.
Если же пользователь в том же объекте меняет значение, то создаётся новый объект, ссылающийся на другой участок памяти
(В отличие от задания один, где данные меняются на одном участке памяти).
<img width="633" height="344" alt="image" src="https://github.com/user-attachments/assets/2403d092-01b9-4b81-b0f8-6fb0a937805f" />

Блок 5. Пистолет стреляет.
В данном задании необходимо было реальзовать стрельбу из пистолета. Пистолет может быть 
с изначальным указанием патронов и без указания. Для двух этих случаев используются два различных конструктора.
Для осуществления

Тестирование.
Функциональное.
Задание 1.
Время.
Условие из задачи.
<img width="946" height="404" alt="image" src="https://github.com/user-attachments/assets/619dac4f-599b-444d-8378-c77c4feee5cb" />
<img width="810" height="248" alt="image" src="https://github.com/user-attachments/assets/6f6dfa37-ed38-425b-a4ff-139b533104bf" />
<img width="805" height="102" alt="image" src="https://github.com/user-attachments/assets/af255d02-e75a-4f3a-8caf-7448c1cecfcc" />
<img width="809" height="218" alt="image" src="https://github.com/user-attachments/assets/fc10cbce-017c-4b88-b619-8c38ce8bae68" />
<img width="739" height="272" alt="image" src="https://github.com/user-attachments/assets/da42eb51-62dd-4c05-9615-897fe98385c6" />
Дом.
Условие из задачи.
<img width="884" height="245" alt="image" src="https://github.com/user-attachments/assets/8e1be5a7-3fb5-49b3-974e-cd422f9796a5" />
<img width="478" height="132" alt="image" src="https://github.com/user-attachments/assets/19039960-23d0-481a-901f-0dcb8894febe" />
<img width="482" height="116" alt="image" src="https://github.com/user-attachments/assets/91ca7dd2-7c8b-4660-9c4c-d43075cc10a5" />
Проверка, что дом не может иметь 0 этажей.
<img width="751" height="262" alt="image" src="https://github.com/user-attachments/assets/364fa879-7e37-4f3f-8373-4a769820fb1c" />

Задание 2.
<img width="554" height="524" alt="image" src="https://github.com/user-attachments/assets/21c4f11d-aacf-4f9c-b24a-77d5c16596a3" />
<img width="599" height="345" alt="image" src="https://github.com/user-attachments/assets/08e266fa-3c74-47bc-952f-86d525ddaa9c" />
<img width="672" height="392" alt="image" src="https://github.com/user-attachments/assets/4d3e1842-3a21-4df5-9226-2584168df6e6" />

Задание 3.
<img width="832" height="752" alt="image" src="https://github.com/user-attachments/assets/a9ea3d6e-3ca7-44c6-8131-faf3596a7189" />
<img width="666" height="678" alt="image" src="https://github.com/user-attachments/assets/1283c349-5d50-4c93-99a0-2181ef9d8816" />
<img width="672" height="701" alt="image" src="https://github.com/user-attachments/assets/caf2f558-abbc-4ce2-bb27-7ce33b13c97f" />

Задание 4.
<img width="909" height="430" alt="image" src="https://github.com/user-attachments/assets/ce3ab039-ebce-49f9-bb11-dff4b6c32942" />

Задание 5.
<img width="711" height="462" alt="image" src="https://github.com/user-attachments/assets/05055920-dddd-4528-80f0-b0c35b858b99" />
<img width="797" height="391" alt="image" src="https://github.com/user-attachments/assets/a89c3896-e0a3-4cb2-903b-9b4b4c157a35" />
<img width="749" height="365" alt="image" src="https://github.com/user-attachments/assets/9b0823df-febb-4257-bf34-6ae4622437ae" />
<img width="804" height="285" alt="image" src="https://github.com/user-attachments/assets/80e8b5f1-b5a6-4841-b335-6b7e830216ab" />
<img width="782" height="225" alt="image" src="https://github.com/user-attachments/assets/e2879783-7040-4458-a570-1d607c2368e4" />

Нефункциональное.
Задание 1.
Время. Проверка на корректность вводимого числа.
<img width="757" height="412" alt="image" src="https://github.com/user-attachments/assets/e1752d7e-62e1-4340-ad2c-81cfb08a882d" />

Дом. Проверка на корректность вводимого числа.
<img width="874" height="508" alt="image" src="https://github.com/user-attachments/assets/18e68cf0-c6ee-497d-bbec-3a5ccf591e98" />

Работа "кнопок" - выполнение подзадач или выход.
<img width="898" height="779" alt="image" src="https://github.com/user-attachments/assets/81dc684e-2ea4-40f8-97a1-f9c9fde6b630" />
<img width="880" height="712" alt="image" src="https://github.com/user-attachments/assets/46ee48b0-fd17-4141-af04-170cf697dffe" />
<img width="856" height="665" alt="image" src="https://github.com/user-attachments/assets/f54e81c6-11d5-4b56-9dc2-aca7f66bbe0d" />
<img width="914" height="753" alt="image" src="https://github.com/user-attachments/assets/7c30c534-f5d5-4b6f-8ea3-6a07393507c6" />

Задание 2. Проверка на корректность вводимой строки(нет лишних знаков).
<img width="459" height="435" alt="image" src="https://github.com/user-attachments/assets/dbcb92ec-1750-447f-b2b5-22c75f947899" />
Проверка на корректность вводимого числа(выбор кнопок)
<img width="506" height="466" alt="image" src="https://github.com/user-attachments/assets/2ffd6842-215a-46ea-9bcd-e72b24c67232" />
<img width="656" height="386" alt="image" src="https://github.com/user-attachments/assets/b8c8a745-0cc9-4365-9716-fad1804e2e55" />

Заданиее 3. Проверка на корректность вводимого числа.
<img width="664" height="748" alt="image" src="https://github.com/user-attachments/assets/73d59c09-d187-467d-aff4-293a4d02bacf" />

Задание 4. Проверка на корректность вводимого числа.
<img width="870" height="524" alt="image" src="https://github.com/user-attachments/assets/63e4ad9e-f790-481b-bf88-4a76c6a73789" />

Задание 5. Проверка на корректность вводимого числа.
<img width="715" height="544" alt="image" src="https://github.com/user-attachments/assets/ff0a28e5-7317-4b1e-adc0-704bfa2377b2" />
