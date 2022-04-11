## Detection of emotions on the face with Keras module.
#

Celem projektu jest nauczenie głebokiej sieci neuronowej rozpoznawać 6 podstawowych emocji:
- Angry, Fear, Happy, Neutral, Sad, Surprise

Moja sieć nauronowa będzie uczyła sie wykrywać emocje na podstawie obrazków zawierających twarze różnych postaci oraz ludzi. Do uczenia wykorzystam popularny zbiór danych FER2013.

![Picture error](https://github.com/Krystiann/BootCamp_project/blob/main/pictures_of_emotions/face%20example1.png)

Oryginalnie w zbiorze danych znajduje się 7 emocji. Niestety dane zawierające 'Disgust' są bardzo niezbalansowane. Dlatego też zdecydowałem się połączyć 'Disgust' z 'Angry'. Obrazy tych dówch etykiet są ciężko odróżnialne nawet dla mnie.

Finalnie moja sieć neuronowa jest wstanie wykrywać poszczególne emocje w czasie rzeczywistym przy pomocy kamerki internetowej.

## Skuteczność

Skuteczność nauczonej sieci to okolo 52 %. Biorąc pod uwagę trudne dane oraz bardzo długi czas uczenia się sieci spowodowany małą mocą obliczeniową moim zdaniem sieć spełnia swoje zadanie.

![Picture error](https://github.com/Krystiann/BootCamp_project/blob/main/pictures_of_emotions/result1.png)

## Rezultat

Poniżej widać że moja sieć nauronowa spełnia swoje zadanie całkiem nieźle.
#


![Picture error](https://github.com/Krystiann/BootCamp_project/blob/main/pictures_of_emotions/merge2.png)
![Picture error](https://github.com/Krystiann/BootCamp_project/blob/main/pictures_of_emotions/merge3.png)
