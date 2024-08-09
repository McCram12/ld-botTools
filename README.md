# ld-botTools

*my first NPM package*

Package structure -> ToDo
> **class ldBot**
> > [parameter] _username_

> > [parameter] _home_

> > [parameter] _admin_

> > [parameter] _id_

> > variable _status_
> > > method _start()_

> > > method _stop()_

> > > method _log()_

> > > method _getLogs(keyword)_
> > > method _registerCommand(command)_
> > > > _CommandSyntax:_
> > > > > Object: `name, aliases, argNum, errorMSG, (method) call()`
> > >
> > > method _sendMSG(message, username)_
> > > method _sendMSGs([messages], username)_
> > > method _getBotCoins()_
> > > > event _msg_
> > > > event _pay_
> > > > event _command_
