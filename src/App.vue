<template>
    <div class="content">
       <div class="stepper">
            <div>test</div>
       </div>
        <div class="row">
            <div class="step">
                <div class="step-content">
                    <div class="step-label">Delivery details</div>
                    <form>
                        <input type="text" placeholder="Name"/>
                        <input type="text" placeholder="Phone Number"/>
                        <textarea placeholder="Delivery Address"/>
                    </form>
                </div>
            </div>
            <div class="summary">
                <div class="summary-content">
                    <div class="summary-label">Summary</div>
                    <p>10 items purchased</p>
                    <hr>
                    <div class="delivery-estimation">
                        <p><b>Delivery estimation</b></p>
                        <p class="font-green">Today by GO-SEND</p>
                    </div>
                    <hr>
                    <div class="payment-method">
                        <p><b>Payment method</b></p>
                        <p class="font-green">Bank transfer</p>
                    </div>
                    <div class="summary-bottom">
                        <table>
                            <tr>
                                <td class="table-header">Cost of goods</td>
                                <td class="price">500,000</td>
                            </tr>
                            <tr>
                                <td class="table-header">Dropshipping fee</td>
                                <td class="price">5,900</td>
                            </tr>
                            <tr>
                                <td class="table-header"><b>GO-SEND</b> shipment</td>
                                <td class="price">15,000</td>
                            </tr>
                            <tr>
                                <td class="total">Total</td>
                                <td class="total price">505,900</td>
                            </tr>
                        </table>
                        <button class="btn-primary">
                            Continue to payment
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    // import HelloComponent from './components/HelloComponent.vue'
    // export default {
    //     components: {
    //         HelloComponent
    //     }
    // }
</script>