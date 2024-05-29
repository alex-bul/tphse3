# Доставка еды — мобильное приложение
Автор: Бульбенков Александр (группа 233, БИ)
### Краткое описание концепции

ПО представляет собой приложение для мобильного устройства, которое позволяет заказать еду с доставкой на дом из
ресторанов города. Сервис будет представлять собой агрегатор, в который заведения общепита смогут добавляться, таким
образом, получая дополнительных клиентов и не разрабатывая собственное приложение для заказа еды. Доставка может
осуществляться как сотрудником сервиса, так и самим рестораном, если у него есть возможность и желание. При этом сервис взимает с каждого заказа определенную комиссию + стоимость доставки, которая высчитывается исходя из
расстояния и погодных условий, если ресторан не доставляет самостоятельно.

В ПО будет 3 основных действующих лица — клиент (заказывает еду), курьер (доставляет еду), заведение (готовит еду, предоставляет
меню). Для каждого будет свой собственный интерфейс, который будет предоставлять нужную функциональность:

1. Клиент — интерфейс для заказа и его отслеживания
2. Курьер — интерфейс для доставки заказов, который позволит брать в работу заказ, видеть адрес клиента, общаться с
   клиентом в чате
3. Заведение — интерфейс для приёма заказов в готовку, изменения его статуса, редактирования меню и проведения акций.

Кроме того, будут и второстепенные акторы (например, повар)

Для заказа клиенту необходимо:

1. указать свой текущий адрес;
2. выбрать один из доступных ресторанов для доставки по данному адресу;
3. наполнить корзину блюдами;
4. оформить заказ, оплатив онлайн.

Далее можно будет отслеживать статус заказа в мобильном приложении и видеть ожидаемое время доставки.


