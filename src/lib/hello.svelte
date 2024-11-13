<h1>inschrijven</h1>

<form>
    <fieldset>
        <legend>persoonlijke gegevens</legend>
        <label for="Voornaam" class="form-label">
            Voornaam*
            <input id="Voornaam"  type="text" required

                    />
        </label>
        <label for="Tussenvoegsel" class="form-label">
            Tussenvoegsel
            <input id="Tussenvoegsel" type="text"/>
        </label>
        <label for="Achternaam" class="form-label">
            Achternaam*
            <input id="Achternaam"  type="text"/>
        </label>
        <label for="functie" class="form-label">
            Functie*
            <input id="functie" type="text"/>
        </label>
        <label for="email" class="form-label">
            E-mail*
            <input id="email" type="email"/>
        </label>
        <label for="Mobiel" class="form-label">
            Mobiel*
            <input id="Mobiel"  type="tel"/>
        </label>
        <label for="Bedrijfsnaam" class="form-label">
            Bedrijfsnaam*
            <input id="Bedrijfsnaam"  type="text"/>
        </label>
        <label for="Bedrijfswebsite" class="form-label">
            Bedrijfswebsite*
            <input id="Bedrijfswebsite"    type="text"/>
        </label>
        <label for="ik wil graag lid worden omdat" class="form-label ">
            ik wil graag lid worden omdat*
            <textarea>

            </textarea>
        </label>
        <label for="FTE">
            FTE*
            <select id="FTE" >
                <option value="">

                </option>
                <option value="1-9">
                    1-9
                </option>
                <option value="10-24">
                    10-24
                </option>
                <option value="25-49">
                    25-49
                </option>
                <option value="50-99">
                    50-99
                </option>
                <option value="100-249">
                    100-249
                </option>
                <option value="250+">
                  250
                </option>
            </select>

        </label>




        <div>
            <a href="bedankt" class="button">Schrijf me in</a>  <svg
                width="16"
                height="16"
                viewBox="0 0 16 16"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
        >
            <path
                    d="M8 3L13.0001 8.0001L8 13.0002"
                    stroke="#222226"
                    stroke-width="1.5"
                    stroke-miterlimit="4.62023"
            />
            <path
                    d="M3 8L13 8"
                    stroke="#222226"
                    stroke-width="1.5"
                    stroke-miterlimit="4.62023"
                    stroke-linejoin="round"
            />
        </svg>
        </div>



    </fieldset>
</form>

<style>
    form{
        color: #666666;
    }
    fieldset{
        border: none;
    }
    legend{
        position: absolute;
        top: 0;
        left: -9999px;
    }
    textarea{
        height: auto;
    }
    input,textarea, select{

        border: none;
    }
    label {
        margin-top: 1.8rem;
        display: flex;
        flex-direction: column;
        justify-content: center;
        width: 100%;
        border-bottom: 1.5px solid black;
    }
    .button{
        border-left: 1px solid #666666;
        border-top: 1px solid #666666;
        border-bottom: 1px solid #666666;
        width: 6rem;
        padding: 0.55rem;
        margin-right: -0.3rem;
        color: #666666;
        text-decoration: none;
    }
    svg{
        border: 1px solid #666666;
        padding: 0.6rem;
        margin-bottom: -0.8rem;
    }



    @media (max-width: 700px) {
            .form-label {
                margin-top: 1.8rem;
                display: flex;
                flex-direction: column;
                justify-content: center;
                width: 100%;
                border-bottom: 1.5px solid black;
            }
        }

    @media (min-width: 800px) {
        fieldset {
            display: grid;
                    grid-template-columns: auto auto;
                    /*background-color: red;*/
            max-width: 700px;
            gap: 1rem;
        }
    }

    /*.form-label {*/
    /*    container-name: main;*/
    /*    container-type: inline-size;*/
    /*}*/
    /*@container main (max-width: 700px) {*/
    /*    .form-label {*/
    /*        margin-top: 1.8rem;*/
    /*        display: flex;*/
    /*        flex-direction: column;*/
    /*        justify-content: center;*/
    /*        width: 100%;*/
    /*        border-bottom: 1.5px solid black;*/
    /*    }*/
    /*}*/

    /*@container main (min-width: 700px) {*/
    /*    .form-label {*/
    /*       display: grid;*/
    /*        grid-template-columns: auto auto;*/
    /*        background-color: red;*/

    /*    }*/
    /*}*/
</style>