# Gonzito.bot
Meu primeiro bot
@bot.command()
async def moeda(ctx):
    lista = ['cara', 'coroa']
    valor = random.choice(lista)
    await ctx.send(f'ops, deu {valor}.') 
