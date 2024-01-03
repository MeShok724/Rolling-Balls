# Rolling-Balls
The billiards game is written in C++ using the SFML library, has non-standard game rules

В рамках данного курсового проекта будет рассматриваться создание игрового приложения "Rolling Balls" для персональных компьютеров. Целью данного проекта является разработка увлекательной и реалистичной игры, которая позволит игрокам насладиться игрой в бильярд. 

При разработке приложения будут использованы следующие классы:
1. Ball – класс, отвечающий за логику и поведение бильярдных шаров.
2. Cue – класс, отвечающий за логику и поведение бильярдного кия.
3. GameMenu – класс, отвечающий за игровое меню.
4. PanelInfo – класс, отвечающий за панель с игровой статистикой.
5. WindowAbout – класс, отвечающий за окно помощи.

Игра начинается с игрового меню, переключение между пунктами которого происходит нажатием клавиш вверх и вниз. Выбранный пункт меню подсвечивается красным цветом. После выбора нужного пункта необходимо нажать Enter. При выборе пункта «Старт» начинается игровой процесс. Чтобы выйти из игры в главное меню, необходимо во время игры нажать клавишу Esc. При выборе пункта «О программе» открывается окно с описанием программы. Чтобы закрыть окно, необходимо нажать клавишу Esc. При выборе пункта «Выход» программа закрывается.

После выбора пункта «Старт» на экране появляется бильярдный стол с шарами и кием. Ход начинает первый игрок, его имя подсвечивается желтым цветом сверху. Игроку необходимо с помощью мыши выбрать траекторию шара. Шар при ударе катится в направлении курсора. Далее необходимо с помощью мыши выбрать силу удара. Чем больше расстояние между курсором и белым шаром, тем сильнее получится удар. После удара шары приходят в движение и, как только шары остановятся, очередь перейдет к следующему игроку. Игроки должны по очереди бить по шарам, пока не забьют все шары или пока один из игроков не забьет белый шар.

Если игроки забили все шары, побеждает игрок, забивший наибольшее количество шаров. Если какой-либо игрок забил белый шар, то он проигрывает.

После окончания игры на экране появляется сообщение с результатами игры. После нажатия клавиши Enter это окно закрывается, и открывается главное меню.

В окне «О программе» выводится информация о разработчике и краткая инструкция. Чтобы выйти в главное меню, нужно нажать Enter.
