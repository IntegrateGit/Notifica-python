# Notifique-me-python
Usando o modulo de notificação por SMS e WhatsApp

# Instalando o modulo via pip
 > ` pip install notifiqueme`

1- Abrindo uma conexão e autenticando
```python
notification = modulo.Notification("ClienteId", "SecretKey")
```

2- Enviando uma notificação no WhatsApp
```python
notification.Send(5531900000000, "Sua mensagem", modulo.NotificationType.WHATSAPP)
```
 > ` Explicação: No método send, requer o numero do celular no tipo inteiro, texto para o destinatário no tipo string(str), e por fim o tipo de notificação`
 
 3- Enviando uma notificação via SMS
 ```python
notification.Send(5531900000000, "Sua mensagem", modulo.NotificationType.SMS)
```
 > ` Explicação: Neste exemplo para enviar um SMS basta colocar o tipo SMS`
 
 3- Enviando uma notificação via WhatsApp e SMS
 ```python
notification.Send(5531900000000, "Sua mensagem", modulo.NotificationType.WHATSAPP_SMS)
```
 > ` Explicação: Neste exemplo para enviar um SMS e uma mensagem no WhatsApp em apenas um envio basta colocar o tipo WHATSAPP_SMS`
 
 >
> ### Outras linguagens
>
> [C#, .net, SDK completo para instalar via nuget](https://github.com/Mrr66/Notifique.me)
> 
> [PHP, exemplo simples](https://github.com/Mrr66/php-notifique-me-whatsApp)


# Gostou do Notifique.me?
Agora basta por a mão na massa e sair notificando seus clientes e sua equipe, há para você que é um DEV dedicado e simplismente de graça basta cadastrar como desenvolvedor.

##### A limites diarios que são aplicado na conta de desenvolvedor diferentemente da conta Business que não a restrição de envio 

>
> ### Crie sua conta hoje mesmo é completamente gratis 
>
>* [Para mais informações acesse](https://cad-notifique-me.herokuapp.com/)
>
>* [Criar uma conta Empresarial](https://cad-notifique-me.herokuapp.com/business)
>
>* [Criar uma conta Desenvolvedor](https://cad-notifique-me.herokuapp.com/developer)
