<script lang="ts">
    import Card from "./Card.svelte";
</script>

<Card title="1 - Liquid or Solid soap recipe?">
    <div class="field">
        <div class="control">
            <label for="radio-naoh" class="radio">
                <input
                    type="radio"
                    name="liquid-or-solid"
                    id="radio-naoh"
                    checked
                />
                Solid Soap - using
                <strong>NaOH</strong> (Sodium Hydroxide)
            </label>
        </div>
        <div class="control">
            <label for="radio-koh" class="radio">
                <input type="radio" name="liquid-or-solid" id="radio-koh" />
                Liquid Soap - using
                <strong>KOH</strong> (Potassium Hydroxide)
            </label>
        </div>
    </div>
</Card>
