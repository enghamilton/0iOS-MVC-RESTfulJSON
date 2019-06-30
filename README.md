# 0iOS-MVC-RESTfulJSON

Desenvolvido por Hamilton uma demonstração de Design Pattern MVC (model view controller) de um app iOS iphone no Xcode 7
em objective C com sdk Cocoa Touch da classe Foundation usando NSURLConnection (deprecated, descontinuada) para requisição 
de banco de dados PHP MySQL Json.

Design Pattern MVC, Padrão de projeto de Software MVC de app para Apple iPhone RESTful webservice JSON com back end PHP MySQL JSON.
Compilação feita com sucesso no Xcode 7.
- M (modelo) usando a classe NSURLConnection (descontinuada pela Apple, porém é funcional ainda, utilizar NSURLSession) recebe do banco de dados (escrito em PHP com MySQL) um objeto JSON.

video demo : https://youtu.be/PTy3mqRcIts

I developed an MVC (model view controller) design pattern using objective C with sdk Cocoa Touch iOS app for iphone on Xcode 7 to a demo for RESTful webservice JSON app.

- M (model) Using from Foundation NSURL Connection (yet deprecated, but works !!!) parsing JSON from a NSString to a NSDictionary iterating objectForKeys to a NSArray.
- V (view) it is a UITableView with includes a UIAlert that shows the JSON parsed. Made in MainStoryboards Scenes.
- C (controller) the viewcontroller that receives data by a Protocol and Delegate to show info on the AlertView.
