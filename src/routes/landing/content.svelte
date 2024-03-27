<script lang="ts">
    import photographer from '$lib/images/photographer.png';
   let ph= photographer;
</script>
<div class="container grid md:grid-cols-2 gap-6">
    <div>
        <img src={ph} alt="" class="w-full">
    </div>
    <div class=" flex flex-col justify-center items-center">
        <h1 class="text-3xl font-bold mb-3">For Events</h1>
        <div class=" container grid sm:grid-cols-2 gap-6 ">
            <div>
                <div>
                    <h1 class="font-bold">Instant photo sharing</h1>
                    <p>Instant availability of photos increases photo sharing on social media.</p>
                </div>
            </div>
            <div >
                <div >
                <h1 class="font-bold">Swift Event Creation</h1>
                <p>Create a dedicated themed events’ page with schedule and sessions.</p>
                </div>
            </div>
            <div>
                <div >
                <h1 class="font-bold">Happy Sponsors</h1>
                <p>Effortlessly push sponsor logo and content to all attendees. Use sponsor insights to measure the efficacy.</p>
                </div>
            </div>
            <div>
                <div>
                <h1 class="font-bold">All in one place</h1>
                <p>It is an event marketing tool, its your DAM, its a CRM, its an expense tracker. Its all in one.</p>
                </div>
            </div>
        </div>
    </div>
</div>