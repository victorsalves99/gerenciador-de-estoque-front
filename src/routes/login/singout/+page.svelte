<script>
	import Button from "../../../lib/components/form/Button.svelte";
    import InputEmail from "../../../lib/components/form/InputEmail.svelte";
	import InputPassword from "../../../lib/components/form/InputPassword.svelte";
	import InputText from "../../../lib/components/form/InputText.svelte";
    import Links from "../../../lib/components/form/Links.svelte";

</script>

<section class="box_login">
    <div class="box_login_container">
        <div class="w-full max-w-sm mx-auto overflow-hidden bg-white rounded-lg shadow-md light:bg-gray-800">
            <div class="px-6 py-4">
                <div class="flex justify-center mx-auto">
                    <img class="w-auto h-7 sm:h-8" src="https://merakiui.com/images/logo.svg" alt="">
                </div>
        
                <h3 class="mt-3 text-xl font-medium text-center text-gray-600 light:text-gray-200">Crie uma conta!</h3>

        
                <form>
                    <InputText 
                        label='Nome completo'
                    />
                    <InputEmail 
                        label='E-mail'
                    />
        
                   <InputPassword 
                        label='Senha'
                   />
                   <InputPassword 
                        label='Confirmar Senha'
                    />
        
                    <div class="flex items-center justify-end mt-4">        
                        <Button 
                            label='Criar conta'
                        />
                    </div>
                </form>
            </div>
        
            <div class="flex items-center justify-center py-4 text-center bg-gray-50 light:bg-gray-700">
                <span class="mx-2  text-gray-600 light:text-gray-200">Voltar a pagina de</span>
        
                <Links 
                    label='Login'
                    color='blue'
                    url='/login/singin'
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