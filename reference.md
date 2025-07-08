# Reference
## Style Guides
<details><summary><code>client.style_guides.<a href="src/acrolinx/style_guides/client.py">get_style_guides</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get all style guides.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import Acrolinx

client = Acrolinx(
    token="YOUR_TOKEN",
)
client.style_guides.get_style_guides()

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**offset:** `typing.Optional[int]` 
    
</dd>
</dl>

<dl>
<dd>

**limit:** `typing.Optional[int]` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_guides.<a href="src/acrolinx/style_guides/client.py">create_style_guide</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import Acrolinx

client = Acrolinx(
    token="YOUR_TOKEN",
)
client.style_guides.create_style_guide()

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**file_upload:** `from __future__ import annotations

core.File` — See core.File for more documentation
    
</dd>
</dl>

<dl>
<dd>

**name:** `typing.Optional[str]` — A friendly name for your style guide to help you identify it later. If left empty, we'll generate one for you.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_guides.<a href="src/acrolinx/style_guides/client.py">get_style_guide</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import Acrolinx

client = Acrolinx(
    token="YOUR_TOKEN",
)
client.style_guides.get_style_guide(
    style_guide_id="style_guide_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**style_guide_id:** `str` — The ID of the style guide.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_guides.<a href="src/acrolinx/style_guides/client.py">delete_style_guide</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import Acrolinx

client = Acrolinx(
    token="YOUR_TOKEN",
)
client.style_guides.delete_style_guide(
    style_guide_id="style_guide_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**style_guide_id:** `str` — The ID of the style guide.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_guides.<a href="src/acrolinx/style_guides/client.py">update_style_guide</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import Acrolinx

client = Acrolinx(
    token="YOUR_TOKEN",
)
client.style_guides.update_style_guide(
    style_guide_id="style_guide_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**style_guide_id:** `str` — The ID of the style guide.
    
</dd>
</dl>

<dl>
<dd>

**name:** `typing.Optional[str]` — The name of the style guide.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Style Checks
<details><summary><code>client.style_checks.<a href="src/acrolinx/style_checks/client.py">create_style_check</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Start a style and brand check run. Returns a workflow ID for each file.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import Acrolinx

client = Acrolinx(
    token="YOUR_TOKEN",
)
client.style_checks.create_style_check()

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**file_upload:** `from __future__ import annotations

core.File` — See core.File for more documentation
    
</dd>
</dl>

<dl>
<dd>

**dialect:** `typing.Optional[Dialects]` — The language variant you'd like us to use for analysis. Choose from American English, British English, or other supported dialects.
    
</dd>
</dl>

<dl>
<dd>

**tone:** `typing.Optional[Tones]` — The tone variation you're aiming for. Options include formal, academic, casual, and other tone variations to match your content goals.
    
</dd>
</dl>

<dl>
<dd>

**style_guide:** `typing.Optional[str]` — The style guide to follow for your content. You can use a custom style guide ID or choose from built-in options like AP, Chicago, or Microsoft style guides.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_checks.<a href="src/acrolinx/style_checks/client.py">get_style_check</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

get the results of a style and brand check run.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import Acrolinx

client = Acrolinx(
    token="YOUR_TOKEN",
)
client.style_checks.get_style_check(
    workflow_id="workflow_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**workflow_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Style Suggestions
<details><summary><code>client.style_suggestions.<a href="src/acrolinx/style_suggestions/client.py">create_style_suggestion</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Start a style and brand suggestion run. Returns a workflow ID for each file.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import Acrolinx

client = Acrolinx(
    token="YOUR_TOKEN",
)
client.style_suggestions.create_style_suggestion()

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**file_upload:** `from __future__ import annotations

core.File` — See core.File for more documentation
    
</dd>
</dl>

<dl>
<dd>

**dialect:** `typing.Optional[Dialects]` — The language variant you'd like us to use for analysis. Choose from American English, British English, or other supported dialects.
    
</dd>
</dl>

<dl>
<dd>

**tone:** `typing.Optional[Tones]` — The tone variation you're aiming for. Options include formal, academic, casual, and other tone variations to match your content goals.
    
</dd>
</dl>

<dl>
<dd>

**style_guide:** `typing.Optional[str]` — The style guide to follow for your content. You can use a custom style guide ID or choose from built-in options like AP, Chicago, or Microsoft style guides.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_suggestions.<a href="src/acrolinx/style_suggestions/client.py">get_style_suggestion</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the results of a suggestion run.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import Acrolinx

client = Acrolinx(
    token="YOUR_TOKEN",
)
client.style_suggestions.get_style_suggestion(
    workflow_id="workflow_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**workflow_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Style Rewrites
<details><summary><code>client.style_rewrites.<a href="src/acrolinx/style_rewrites/client.py">create_style_rewrite</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Start a rewrite run for one or many files. Returns a workflow ID for each file.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import Acrolinx

client = Acrolinx(
    token="YOUR_TOKEN",
)
client.style_rewrites.create_style_rewrite()

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**file_upload:** `from __future__ import annotations

core.File` — See core.File for more documentation
    
</dd>
</dl>

<dl>
<dd>

**dialect:** `typing.Optional[Dialects]` — The language variant you'd like us to use for analysis. Choose from American English, British English, or other supported dialects.
    
</dd>
</dl>

<dl>
<dd>

**tone:** `typing.Optional[Tones]` — The tone variation you're aiming for. Options include formal, academic, casual, and other tone variations to match your content goals.
    
</dd>
</dl>

<dl>
<dd>

**style_guide:** `typing.Optional[str]` — The style guide to follow for your content. You can use a custom style guide ID or choose from built-in options like AP, Chicago, or Microsoft style guides.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_rewrites.<a href="src/acrolinx/style_rewrites/client.py">get_style_rewrite</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the results of a rewrite run.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import Acrolinx

client = Acrolinx(
    token="YOUR_TOKEN",
)
client.style_rewrites.get_style_rewrite(
    workflow_id="workflow_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**workflow_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

