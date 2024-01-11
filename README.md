# CV pet-project: Insulators_defects

Обучение DL-модели классификации дефектов электрических изоляторов.
Три типа дефектов: скол, трещина, грязь. Дефекты не взаимоисключающие. Изолятор может быть одновременно и со сколом, и с грязью или со всеми тремя дефектами.
Написан полный код обучения и валидации на pytorch. В качестве метрики использовалась F1 (отдельно для каждого класса и общая). Проводится логирование метрик и лосса, используется tensorboard.
Датасет несбалансированный по количеству классов. Поэтому предложено решение, как иметь с этим дело - аугментация данных. 

#

<img align='center' src="https://github.com/rectorkipa/CV-Insulators_defects/blob/main/scrn1_images.JPG" width="640">

#

<img align='center' src="https://github.com/rectorkipa/CV-Insulators_defects/blob/main/scrn2_model.JPG" width="640">

#

<img align='center' src="https://github.com/rectorkipa/CV-Insulators_defects/blob/main/scrn3_scalars.JPG" width="640">
