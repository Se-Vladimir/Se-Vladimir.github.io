Куски кода py представляющие интерес

    def clone(self, args=()):              # optional constructor args
        new = Toplevel()                   # make new in-process version of me
        myclass = self.__class__           # instance's (lowest) class object
        myclass(new, *args)                # attach/run instance to new window

"Программный продукт должен становиться более специфическим, в процессе наследования, по мере углубления в иерархию програмного кода, но на самом верху, всё должно быть максимально универсальным."
