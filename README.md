# Atividade-While-Senha
Peça ao usuário que insira uma senha e repita o pedido até que a senha correta seja digitada. A senha correta é "12345". Quando a senha estiver correta, exiba uma mensagem de sucesso e encerre o programa.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace AtividadeWhileSenha
{
public class Program
{
static void Main(string[] args)
{
            string senha;

  Console.Write("Digite a senha: ");
            senha = Console.ReadLine();

  while (senha != "12345")
            {
                Console.WriteLine("Senha incorreta. Tente novamente.");
                Console.Write("Digite a senha: ");
                senha = Console.ReadLine();
            }

  Console.WriteLine("Acesso concedido!");
            Console.ReadKey();
        }
    }
}
