O que é {
        
        O Laziot é uma plataforma web middleware que permite a comunicação entre si de dispositivos iot com suporte à mqtt.
        
        A comunicação é realizada com mensagens mqtt enviada de um dispositivo ou mais dispositivos emissores para o servidor da aplicação, aplicando (ou não) regras de negócio e enviando (ou não) uma mensagem nova aos dispositivos receptores vinculados à um ou mais dispositivos emissores cadastrados.
    }

Como nasceu {
    
        O Laziot nasceu de uma necessidade real e bastante dolorida fisicamente, após várias quedas durante a noite em uma escada de concreto/cimento, me peguei perguntando o porque de uma escada que poderia ser mortal nessa condição, não estava iluminada ainda e a resposta veio quase tão rápido quanto meu último tombo hahahahaha.

        Após ter estudado por uns 4 anos aproximadamente, eletrônica, iot e elétrica de forma auto-didata por hobby, uni estes conhecimentos e muitas horas de prática com componentes eletrônicos adquiridos durante este período, com minha experiência em desenvolvimento de software, para chegar na solução do meu problema e também no que viria a ser meu tcc (entregue dez/2022).

        A ideia era bastante simples(spoiler: descobri mais tarde que não era), utilizar sensores simples e baratos mas com pleno funcionamento, enviando os dados destes sensores por wifi à uma plataforma e se os dados recebidos estivessem dentro do configurado na plataforma, seria enviado um novo sinal por wifi com o comando de ligar ou desligar fitas de led instaladas nas áreas de baixa(ou sem) iluminação na minha casa. Sendo assim, o funcionamento seria basicamente o seguinte: um sensor de presença detectaria movimento no topo e na base da escada, quando esse sensor fizesse a detecção, enviaria um sinal via wifi para a plataforma(Laziot) e localizaria algum comando para aquele sinal(se houvesse algum cadastrado pelo usuário), supondo que havesse a ação de ligar as luzes dessa área externa, seria enviado um sinal pela plataforma para um dispositivo receptor que faria o acionamento das luzes pelo tempo pré-determinado ou até que outro sensor enviasse um sinal para desligar as luzes.

        O projeto foi concebido pensando em diversas futuras aplicações, como por exemplo, controlar inteiramente(luz, temperatura e umidade) algum tipo de pequeno cultivo dentro de casa, visando quem tem dificuldade de dedicar tempo e dedicação à platinhas domésticas mas gostaria de te-lás saudáveis em sua decoração ou também, ligar qualquer dispositivo elétrico, em um determinado horário em dias configuráveis (uma cafeteira por exemplo).
}

    Tecnologias/Ferramentas utilizadas {
        Back-end {
            Java
            Spring boot
            Mqtt
            Redis
            Log4j
        }
        
        Front-end {
            Node.js
            React.js
            Material.ui
            Typescript.js
            Sass
        }

        Banco de Dados {
            Mysql
        }

        Estrutura {
            Docker
            Portainer
        }

    }

    Como funciona {
        Em andamento ... atualização em breve
    }