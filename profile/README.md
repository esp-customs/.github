## ESP CUSTOMS
### <img src="https://images.emojiterra.com/twitter/v13.1/512px/1f1ea-1f1f8.png" alt="Español" width="20px"> Español
`EspCustoms es un proyecto empresarial que empezo a mediados de 2020 y ha ido escalando cada vez a mas, siendo actualmente uno de los bots de discord con mas funciones activas.`

`(Por razones de seguridad, MongoDB nunca se conecta directamente al Web Frontend.)`

### <img src="https://images.emojiterra.com/twitter/v13.1/512px/1f1ec-1f1e7.png" alt="English" width="20px"> English
`EspCustoms is an entrepreneurial project that started in mid-2020 and has been escalating more and more, being currently one of the most active discord bots.`

`(For security reasons MongoDB never connects directly to the Web Frontend.)`

### How our services work
```mermaid
flowchart LR
	C("Web Backend\n(Express)") --> A("MongoDB")
	B(("API")) --> D("Web Frontend\n(Angular)")
	B --> C
	C --> B
	A --> C
	D --> B
	C --> 108697("Moduls")
	108697 --> C
	707316("Discord.js") --> 108697
	472449("CanvaCard") --> 108697
	250033("Twitch API") --> 108697
	200431("Youtube API") --> 108697
	351108("@espcustomss/oauth") --> 108697
```
