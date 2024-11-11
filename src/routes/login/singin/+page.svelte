<script>
	import Button from "../../../lib/components/form/Button.svelte";
import InputEmail from "../../../lib/components/form/InputEmail.svelte";
	import InputPassword from "../../../lib/components/form/InputPassword.svelte";
import Links from "../../../lib/components/form/Links.svelte";

</script>

<section class="box_login">
    <div class="box_login_container">
        <div class="w-full max-w-sm mx-auto overflow-hidden bg-white rounded-lg shadow-md light:bg-gray-800">
            <div class="px-6 py-4">
                <div class="flex justify-center mx-auto">
                    <img class="w-auto h-7 sm:h-8" src="https://merakiui.com/images/logo.svg" alt="">
                </div>
        
                <h3 class="mt-3 text-xl font-medium text-center text-gray-600 light:text-gray-200">Bem vindo!</h3>
        
                <p class="mt-1 text-center text-gray-500 light:text-gray-400">Faça login ou crie uma conta</p>
        
                <form>
                    <InputEmail 
                        label='E-mail'
                    />
        
                   <InputPassword 
                        label='Senha'
                   />
        
                    <div class="flex items-center justify-between mt-4">
                        <Links 
                            label='Esqueceu a senha?'
                        />
        
                        <Button 
                            label='Login'
                        />
                    </div>
                </form>
            </div>
        
            <div class="flex items-center justify-center py-4 text-center bg-gray-50 light:bg-gray-700">
                <span class="mx-2  text-gray-600 light:text-gray-200">Não tem um conata? </span>
        
                <Links 
                    label='Registre-se'
                    color='blue'
                    url='/login/singout'
                />
            </div>
        </div>
    </div>
</section>




<style>
    .box_login {
        min-width: 100vw;
        min-height: 100vh;
        max-width: 100vw;
        max-height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .box_login_container {
        max-width: 70vw;
        max-height: 70%;
        min-width: 70vw;
        min-height: 70%;
    }

</style>