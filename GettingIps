import java.io.BufferedReader;
import java.io.BufferedWriter;
import java.io.File;
import java.io.FileReader;
import java.io.FileWriter;
import java.io.IOException;
import java.io.InputStreamReader;
public class ColetaDeDados {
    public static void main(String[] args) throws IOException, InterruptedException {
        Character c;
        String s;
        File arquivo = new File(args[0]); /*o endereço do arquivo de texto contendo o numero dos IPs deve ser informado no args[0]*/
        FileReader arq = new FileReader(arquivo);
        BufferedReader lerArq = new BufferedReader(arq);
        String line = lerArq.readLine();
        String str;
        File arqui = new File(arg[1]); /*o endereço destino dos dados coletados deve ser informado no args[1]*/
        arqui.createNewFile();
        FileWriter escreve = new FileWriter(arqui);
        BufferedWriter esc = new BufferedWriter(escreve);
        while (line != null) {
            Process p = Runtime.getRuntime().exec("cmd /c tracert " + line);
            BufferedReader stdInput = new BufferedReader(new InputStreamReader(p.getInputStream()));
            while ((str = stdInput.readLine()) != null) {
                                System.out.println(str);
                esc.append(str);
                esc.newLine();                               
            }
             stdInput.close();         
            line = lerArq.readLine();
        }
        esc.close();           
    }
}
