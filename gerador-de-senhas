import random
import string

def gerar_senha(tamanho=12):
    # Define os caracteres permitidos: letras, números e símbolos
    caracteres = string.ascii_letters + string.digits + string.punctuation
    
    # Gera a senha sorteando os caracteres
    senha = ''.join(random.choice(caracteres) for _ in range(tamanho))
    return senha

if __name__ == "__main__":
    print("=== Gerador de Senhas Seguras ===")
    tamanho_desejado = 16
    senha_gerada = gerar_senha(tamanho_desejado)
    
    print(f"Sua nova senha de {tamanho_desejado} caracteres é:")
    print(f"👉 {senha_gerada}")
