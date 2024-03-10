# YouTubeCoin-YTB-TRC20-Contract





Заменить в файле Token.sol значение на 19 и 20 строке как на примере ниже...











 constructor () public TRC20Detailed("YouTubeCoin", "YTB", 8) {        // Заменить название монеты и тикер токена на ваши... Пример TRC20Detailed("Bitcoin", "BTC", 8)
        _mint(msg.sender, 21000000 * (10 ** uint256(decimals())));     // Заменить колличество монет на нужное... Пример у Bitcoin полная эмиссия  msg.sender, 21000000
