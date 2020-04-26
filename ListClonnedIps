public static void main(String[] args) throws FileNotFoundException, IOException {
        List<String> IPs = Files.readAllLines(Paths.get(args[0])); /*endereço dos dados a serem filtrados deve ser informado no args[0]*/
        String IP;
        for(int i = 0;i<IPs.size();i++){
            IP = IPs.get(i);
            IP = IP.trim();
            System.out.println("TESTE PARA = "+IP+" DA LINHA = "+(i+1));
            for(int j = 0;j<IPs.size();j++){
                if(IP.compareTo(IPs.get(j)) == 0){
                    System.out.println(IPs.get(j)+"     Linha: "+(j+1));
                }
            }
            System.out.println("==============================\n");
        }
}

