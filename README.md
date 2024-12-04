
# Лабораторная работа 4.

Я запустил `aafire` в контейнере, создав Dockerfile, и заодно установив утилиту `ping`:

![VirtualBoxVM_Qgb93xESF6](https://github.com/user-attachments/assets/d580863b-53ed-4e8f-9b74-6752cba4e813)

![VirtualBoxVM_bkxE6OZByL](https://github.com/user-attachments/assets/d4822a73-a56c-4a81-9539-4f7eaf1f2997)

>Ну, демонов призвали, можно и огонь разжечь.

Далее, создал два контейнера на основе образа `aafire`:

![VirtualBoxVM_gYZl1PfQv9](https://github.com/user-attachments/assets/2f84d79b-f738-4a3e-b8e1-cd7f5b6dbad1)

Проверил, что они работают:

![VirtualBoxVM_vg38qldgNZ](https://github.com/user-attachments/assets/110d677e-6dc7-4d9b-86bc-ab870c01293f)

Создал сеть и подключил контейнеры к ней:

![VirtualBoxVM_HIF2TNLJIx](https://github.com/user-attachments/assets/89fbfb6a-7287-438f-a9c8-a03a7bff8462)

Удалил ненужное т.к. все место на устройстве было занято:

![VirtualBoxVM_KcnK9mRTsK](https://github.com/user-attachments/assets/672701b1-0f97-4c27-b550-ed6e55ff2ed5)

Ну, и наконец, проверил соединение между сетями с помощью `ping`:

![VirtualBoxVM_5x6vp6kchF](https://github.com/user-attachments/assets/2d0c94ad-2b4f-4a41-a22e-d33c9548b9b1)

Как видно, все прекрасно работает.



