# ProjetoForms1.Produtoinformation
Criar as propriedades dos dados do produto.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ProjetoForms1
{
    public class Produtoinformation
    {
        //atalho propfull+tab tab

  private int codigo;

  public int Codigo
        {
            get { return codigo; }
            set { codigo = value; }
        }
        private string fornecedo_codigo;

  public string Fornecedo_codigo
        {
            get { return fornecedo_codigo; }
            set { fornecedo_codigo = value; }
        }

  private string marca_codigo;

  public string Marca_codigo
        {
            get { return marca_codigo; }
            set { marca_codigo = value; }
        }

  private string nome;

  public string Nome
        {
            get { return nome; }
            set { nome = value; }
        }

  private string quantidade;

  public string Quantidade
        {
            get { return quantidade; }
            set { quantidade = value; }
        }

  private string valorunitario;

  public string Valorunitario
        {
            get { return valorunitario; }
            set { valorunitario = value; }
        }

  private string descricao;

  public string Descricao
        {
            get { return descricao; }
            set { descricao = value; }
        }
    }
}
