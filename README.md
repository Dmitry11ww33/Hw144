# Hw144

Класс БанковскийАккаунт должен хранить информацию о владельце, балансе
Метод show должен показать информацию об объекте. Создайте два разных объекта и вызовите у них метод show

class BankAccount:
    def __init__(self, owner, balance):
        self.owner = owner
        self.balance = balance

    def show(self):
        print(f"Owner: {self.owner}")
        print(f"Balance: {self.balance}")

# Создаем два объекта класса BankAccount
account1 = BankAccount("Иванов Иван", 1000)
account2 = BankAccount("Петров Петр", 500)

# Вызываем метод show для каждого объекта
print("Информация о счете 1:")
account1.show()

print("\nИнформация о счете 2:")
account2.show()
