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

            Console.WriteLine("Informe a senha: ");
            senha = Console.ReadLine();
            senha = senha.ToLower();

            while (senha != "12345")
            {
                Console.WriteLine("Digite a senha correta: ");
                senha = Console.ReadLine();
            }
            Console.WriteLine("Acesso Liberado - O.K.!");

            Console.ReadKey();
        }
    }
}
