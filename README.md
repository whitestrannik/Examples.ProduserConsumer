# Examples.ProducerConsumer

# Класс Consumer
- выполняет поочередно задачи (Action), добавленные посредством методов Add;
- позволяет отменять еще  не выполненные задачи (посредством передачи CancelationToken в метод Add);
- позволяет контролировать статус каждый задачи (посредством Task, возвращаемого методом Add);
- реализует IDisposable (но без Finalazer - для упрощения);
- тесты добавлены только для режима работы с одним потоком - т.е. для варианта, когда задачи выполняются
  последовательно одна за другой;

Классы Producer\Factory имеют исключительно вспомогательный характер;