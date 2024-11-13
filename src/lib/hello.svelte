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

    @media (min-width: 700px) {
        fieldset {
            display: grid;
                    grid-template-columns: auto auto;
                    /*background-color: red;*/
            max-width: 700px;
            column-gap: 1rem;
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