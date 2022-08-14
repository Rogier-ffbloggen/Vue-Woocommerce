<template>
    <div class="table-container">
        <table class="table">
        <thead>
            <tr>
            <th></th>
            <th><abbr title="Product">Product</abbr></th>
            <th>Prijs</th>
            <th>Aantal</th>
            <th>Subtotaal</th>
            </tr>
        </thead>
        <tbody>
            <tr>
            <div class="box mt-5">
            <article class="media">
                <div class="media-left">
                <figure class="image is-24x24">
                    <img src="../assets/rompertje5.1.jpg" alt="Image">
                </figure>
                </div>
                <div class="media-content">
                <div class="content">
                    <p>
                        <button class="delete"></button>
                    </p>
                </div>
                </div>
            </article>
            </div>
            <th>Romper met auto</th>
            <td>€23.99</td>
            <td>
                <div class="select is-small">
                    <select>
                        <option>1</option>
                        <option>2</option>
                        <option>3</option>
                        <option>4</option>
                        <option>5</option>
                    </select>
                </div>
            </td>
            <td>€23.99</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
            <th><abbr title="Product bijwerken">
                <button class="button is-dark">Product bijwerken</button></abbr></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            </tr>
        </tfoot>    
        </table>
    </div>
</template>