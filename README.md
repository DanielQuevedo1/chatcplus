Sisteminha basico de envio de mensagens com c++

bibliotecas usadas:

#include<iostream>	//usado para invocar funções comuns como cout,cin
#include<conio.h>	//usada para console input/output
#include<string.h>	//usada para manipular string
#include<windows.h>	//usada para mover o cursor
#include<time.h>	//data e hora
#include<fstream>	//manipulação de arquivos
#include<iomanip>	//controlar o formato de entrada e saída de dados no console

Explicação sobre cada uma delas:

#include<iostream>: Biblioteca padrão de entrada e saída. Usada para funções como cout (saída no console), cin (entrada de dados do usuário), entre outras.

#include<conio.h>: Fornece funções de entrada e saída de console, como getch(), que é usado para capturar uma tecla sem precisar apertar Enter. Não faz parte do padrão C++ e é mais comum em ambientes Windows (antigos).

#include<string.h>: Fornece funções para manipulação de strings de estilo C, como strlen(), strcpy(), etc. No C++, é mais comum usar a biblioteca #include<string> para manipular strings modernas (classe std::string).

#include<windows.h>: Biblioteca específica para o sistema operacional Windows, contendo funções para controlar o sistema e o console, como mover o cursor, manipular janelas, e controlar threads e processos.

#include<time.h>: Fornece funções para trabalhar com data e hora, como time(), ctime(), etc.

#include<fstream>: Usada para manipulação de arquivos, permitindo abrir, ler, escrever e fechar arquivos usando classes como ifstream (entrada de arquivo) e ofstream (saída de arquivo).

#include<iomanip>: Fornece manipuladores para controlar o formato de entrada e saída de dados no console, como setprecision (para formatar a precisão dos números), setw (para definir a largura dos campos), entre outros.
