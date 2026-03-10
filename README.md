Remote SYSDIAGNOSE Modifier 📲

Este projeto permite alterar arquivos .tar do iCloud Drive remotamente usando um dispositivo Android.

1. O script monitora o iCloud Drive e baixa o arquivo .tar.gz quando ele aparece.
2. O arquivo é extraído, e arquivos específicos dentro de logs/MCState/Shared e logs/Networking são modificados usando dd ou replace, permitindo alterar o conteúdo sem quebrar o código binário.
3. O .tar.gz é recriado e enviado de volta para o iCloud Drive, mantendo o mesmo nome e estrutura.
