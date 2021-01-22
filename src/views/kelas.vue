<template>
    <ion-page>
        <ion-header>
            <ion-toolbar color="primary">
                <ion-title>
                    Kelas
                </ion-title>
            </ion-toolbar>
        </ion-header>

        <ion-content>
            <ion-list>
                <ion-item :routerLink="'/kelas/1'">
                    <ion-label>
                        <h2>Kelas 1 <span class="ruang">No Ruang</span></h2>
                        <p>Mata Kuliah</p>
                    </ion-label>
                </ion-item>
                <ion-item :routerLink="'/kelas/1'">
                    <ion-label>
                        <h2>Kelas 2 <span class="ruang">No Ruang</span></h2>
                        <p>Mata Kuliah</p>
                    </ion-label>
                </ion-item>
                <ion-item :routerLink="'/kelas/1'">
                    <ion-label>
                        <h2>Kelas 3 <span class="ruang">No Ruang</span></h2>
                        <p>Mata Kuliah</p>
                    </ion-label>
                </ion-item>
                <ion-item :routerLink="'/kelas/1'">
                    <ion-label>
                        <h2>Kelas 4 <span class="ruang">No Ruang</span></h2>
                        <p>Mata Kuliah</p>
                    </ion-label>
                </ion-item>
            </ion-list>
        </ion-content>
    </ion-page>
</template>

<script>
    import {
        IonPage,
        IonHeader,
        IonToolbar,
        IonTitle,
        IonContent,
        IonList,
        IonItem,
        IonLabel
    } from '@ionic/vue'

    import { defineComponent } from 'vue';
    export default defineComponent({
        components: {
            IonPage,
            IonHeader,
            IonToolbar,
            IonTitle,
            IonContent,
            IonList,
            IonItem,
            IonLabel
        }
    })
</script>

<style scoped>
.ruang {
    float: right;
    align-items: center;
    display: flex;
}
</style>