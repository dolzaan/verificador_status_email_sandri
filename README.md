🔧 Automação de Monitoramento e Relatórios Diários de Infraestrutura

Nos últimos dias, finalizei um projeto interno que automatiza completamente a verificação do ambiente de TI do Grupo Sandri, com foco 
em:

✅ Status dos servidores por unidade
✅ Verificação de backups dos PDVs
✅ Análise de arquivos de integração da Máxima Tech
✅ Status e capturas dos DVRs via RTSP com FFmpeg
✅ Geração de relatório em HTML + envio automático por e-mail com anexos

A automação foi desenvolvida com PowerShell, integrando:
-Testes de conectividade via Test-Connection
-Capturas de imagens via FFmpeg
-Organização e compactação de arquivos
-Geração de relatório HTML com status visual
-Envio automático via SMTP seguro com anexo ZIP

Essa solução tem ajudado nossa equipe a antecipar falhas, garantir que backups estejam atualizados e manter um controle visual sobre os sistemas de segurança, tudo isso de forma centralizada e diária, sem intervenção manual.

Se você também está buscando melhorar a visibilidade e controle da sua infraestrutura, automações como essa podem ser um grande diferencial.
