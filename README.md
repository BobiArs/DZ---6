import colorama
from colorama import Fore, Back

#Ініціалізація colorama
colorama.init()

#Fore.GREEN та Back.BLACK використовуються для задання кольорів тексту та фону, що покращує візуальну привабливість виводу
print(Fore.GREEN + 'Текст стає зеленим' + Fore.RESET)
print(Back.BLACK + 'Фон стає чорним' + Back.RESET)

#Повторна ініціалізація
colorama.reinit()
