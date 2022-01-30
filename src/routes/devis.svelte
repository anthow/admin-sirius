
<header class="bg-green-600 text-white p-2 flex space-around mb-10">
    <h1 class="text-3xl w-11/12 m-auto"> Administration Sirius</h1>
    <button class="bg-white text-green-600 rounded p-2"> nouveau devis</button>
   </header>

   <form class=" w-6/12 m-auto text-center flex flex-col ">
       <label for="client">Nom du client</label>
       <input class="border w-1/2 m-auto" name="client" id="client" type="text" />
       <label>n°TVA client</label>
       <input class="border w-1/2 m-auto" type="text" />
       <label>n° BCE client</label>
       <input class="border w-1/2 m-auto" type="text" />
       <label>statut juridique</label>
       <input class="border w-1/2 m-auto" type="text" />
       <label>titre du devis</label>
       <input class="border w-1/2 m-auto" type="text" />
       <label>date de livraison</label>
       <p>c'est à cette date là que la devis sera envoyé au client</p>
       <input class="border w-1/2 m-auto" type="date" />
       <label>montant hors TVA</label>
       <input class="border w-1/2 m-auto" type="number" />
       <label>adresse mail client</label>
       <input class="border w-1/2 m-auto" type="email" />
       <label>Description</label>
       <textarea class="border w-9/12 m-auto"  maxlength="500"  rows="10"> </textarea>
       <input type="submit" value="Envoyer le formulaire" class="mb-10 bg-green-600 w-min text-white p-2 m-auto">


   </form>