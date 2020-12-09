Куски кода py и цитаты представляющие интерес:

    def clone(self, args=()):              # optional constructor args
        new = Toplevel()                   # make new in-process version of me
        myclass = self.__class__           # instance's (lowest) class object
        myclass(new, *args)                # attach/run instance to new window

"Программный продукт должен становиться более специфическим, в процессе наследования, по мере углубления в иерархию програмного кода, но на самом верху, всё должно быть максимально универсальным. Лучше разбивать программу на модули, каждый из которых содержит в себе классы, созданных для реализации какой-то определенной конкретной задачи, решение которой берет на себя какая-то часть программы. При этом должен быть главный модуль и второстепенные. Таким образом, вся программа состоит из частей, часть программы - это модуль."

"Модульная архитектура python и короткий цикл разработки хорошо соответствуют напряженным требованиям создания приложений для Интернета."
